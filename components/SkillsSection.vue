<template>
  <v-container id="skills">
    <h2>Skills & Ferramentas</h2>
    <v-row>
      <v-col cols="12" md="6">
        <h3>Frontend</h3>
        <ul>
          <li>HTML, CSS, JavaScript</li>
          <li>React, Redux</li>
        </ul>
      </v-col>
      <v-col cols="12" md="6">
        <h3>Backend</h3>
        <ul>
          <li>Node.js, Express</li>
          <li>PHP</li>
        </ul>
      </v-col>
    </v-row>
    <v-row>
      <v-col cols="12" md="6">
        <h3>Bancos de Dados</h3>
        <ul>
          <li>MySQL</li>
          <li>MongoDB</li>
        </ul>
      </v-col>
      <v-col cols="12" md="6">
        <h3>DevOps & Ferramentas</h3>
        <ul>
          <li>Docker, Git, GitHub</li>
          <li>Firebase, Heroku</li>
        </ul>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: 'SkillsSection',
}
</script>

<style scoped>
h2, h3 {
  color: #2196f3;
}

ul {
  color: #333333;
}
</style>
