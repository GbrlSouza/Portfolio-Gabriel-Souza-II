<template>
  <v-container id="about">
    <v-row>
      <v-col cols="12" md="4">
        <v-img
          src="https://via.placeholder.com/200"
          alt="Foto de João Silva"
          max-width="200"
        ></v-img>
      </v-col>
      <v-col cols="12" md="8">
        <h2>Sobre Mim</h2>
        <p>
          Sou um desenvolvedor Full Stack Jr. apaixonado por criar soluções web modernas. 
          Tenho experiência em React, Node.js, e bancos de dados SQL/NoSQL. Sempre em busca de 
          novas oportunidades para expandir minhas habilidades e colaborar em projetos desafiadores.
        </p>
        <h3>Formação Acadêmica</h3>
        <p>Bacharelado em Ciência da Computação - Universidade XYZ - 2022</p>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: 'AboutMeSection',
}
</script>

<style scoped>
h2 {
  color: #2196f3;
}

p {
  color: #333333;
}
</style>
