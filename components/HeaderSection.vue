<template>
  <v-toolbar flat dark color="blue darken-3">
    <v-toolbar-title>João Silva | Full Stack Developer Jr</v-toolbar-title>
    <v-spacer></v-spacer>
    <v-btn text to="#about">Sobre</v-btn>
    <v-btn text to="#skills">Skills</v-btn>
    <v-btn text to="#projects">Projetos</v-btn>
    <v-btn text to="#contact">Contato</v-btn>
  </v-toolbar>
</template>

<script>
export default {
  name: 'HeaderSection',
}
</script>

<style scoped>
.v-toolbar-title {
  font-weight: bold;
}
</style>
