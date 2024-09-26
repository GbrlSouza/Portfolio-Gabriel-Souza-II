<template>
  <v-container id="ideas">
    <h2>Ideias de Projetos Futuros</h2>
    <v-row>
      <v-col cols="12" md="6" v-for="idea in ideas" :key="idea.title">
        <v-card>
          <v-card-title>{{ idea.title }}</v-card-title>
          <v-card-text>{{ idea.description }}</v-card-text>
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: 'IdeasSection',
  data() {
    return {
      ideas: [
        {
          title: 'App de Mensagens com IA',
          description: 'App de mensagens com respostas automáticas via API de IA e tradução para português.',
        },
        // Adicione mais ideias
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
