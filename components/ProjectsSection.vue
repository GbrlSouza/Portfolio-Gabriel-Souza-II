<template>
  <v-container id="projects">
    <h2>Projetos</h2>
    <v-row>
      <v-col cols="12" md="6" v-for="project in projects" :key="project.title">
        <v-card>
          <v-img :src="project.image" height="200px"></v-img>
          <v-card-title>{{ project.title }}</v-card-title>
          <v-card-subtitle>{{ project.technologies }}</v-card-subtitle>
          <v-card-text>{{ project.description }}</v-card-text>
          <v-card-actions>
            <v-btn text :href="project.demoLink" target="_blank">Demo</v-btn>
            <v-btn text :href="project.repoLink" target="_blank">GitHub</v-btn>
          </v-card-actions>
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: 'ProjectsSection',
  data() {
    return {
      projects: [
        {
          title: 'Sistema de Agendamento HelpHair',
          technologies: 'Vue.js, Firebase',
          description: 'Um sistema de agendamento de cortes de cabelo.',
          demoLink: '#',
          repoLink: '#',
          image: 'https://via.placeholder.com/300'
        },
        // Adicione mais projetos
      ]
    }
  }
}
</script>

<style scoped>
h2 {
  color: #2196f3;
}
</style>
