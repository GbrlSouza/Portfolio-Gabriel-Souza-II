<template>
  <v-app>
    <v-container>
      <!-- Header -->
      <HeaderSection />

      <!-- Sobre Mim -->
      <AboutMeSection />

      <!-- Skills -->
      <SkillsSection />

      <!-- Projetos -->
      <ProjectsSection />

      <!-- Ideias/Projetos Futuro -->
      <IdeasSection />

      <!-- Contato -->
      <ContactSection />

      <!-- Footer -->
      <FooterSection />
    </v-container>
  </v-app>
</template>

<script>
import HeaderSection from './components/HeaderSection.vue';
import AboutMeSection from './components/AboutMeSection.vue';
import SkillsSection from './components/SkillsSection.vue';
import ProjectsSection from './components/ProjectsSection.vue';
import IdeasSection from './components/IdeasSection.vue';
import ContactSection from './components/ContactSection.vue';
import FooterSection from './components/FooterSection.vue';

export default {
  components: {
    HeaderSection,
    AboutMeSection,
    SkillsSection,
    ProjectsSection,
    IdeasSection,
    ContactSection,
    FooterSection,
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap');

html, body {
  font-family: 'Montserrat', sans-serif;
  margin: 0;
  padding: 0;
}

.v-container {
  padding: 20px;
  background-color: #ffffff;
}

.v-app {
  background-color: #000000;
}

</style>
