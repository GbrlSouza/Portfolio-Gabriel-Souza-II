<template>
  <v-footer color="blue darken-3" dark>
    <v-container>
      <v-row>
        <v-col>
          <p>© 2024 João Silva. Todos os direitos reservados.</p>
        </v-col>
        <v-col>
          <v-icon small>mdi-github</v-icon>
          <v-icon small>mdi-linkedin</v-icon>
          <v-icon small>mdi-twitter</v-icon>
        </v-col>
      </v-row>
    </v-container>
  </v-footer>
</template>

<script>
export default {
  name: 'FooterSection',
}
</script>

<style scoped>
p {
  margin: 0;
}
</style>
