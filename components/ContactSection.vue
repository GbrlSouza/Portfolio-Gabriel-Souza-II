<template>
  <v-container id="contact">
    <h2>Contato</h2>
    <v-form>
      <v-text-field label="Nome" required></v-text-field>
      <v-text-field label="E-mail" required></v-text-field>
      <v-textarea label="Mensagem" required></v-textarea>
      <v-btn color="blue darken-3" dark>Enviar</v-btn>
    </v-form>
  </v-container>
</template>

<script>
export default {
  name: 'ContactSection',
}
</script>

<style scoped>
h2 {
  color: #2196f3;
}
</style>
