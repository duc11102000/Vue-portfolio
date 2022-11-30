<template>
  <div>
    <HeroCard></HeroCard>
    <MainCard></MainCard>
    <projects-card></projects-card>
    <ContactCard></ContactCard>
    <footer-card></footer-card>
  </div>
</template>

<script>
import MainCard from "./components/MainCard.vue";
import ProjectsCard from "./components/ProjectsCard.vue";
import HeroCard from "./components/HeroCard.vue";
import FooterCard from "./components/FooterCard.vue";
import ContactCard from "./components/ContactCard.vue";
export default {
  name: "App",
  components: {
    HeroCard,
    MainCard,
    ProjectsCard,
    ContactCard,
    FooterCard,
  },
};
</script>

<style>
body {
  margin: 0;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
  color: #2c3e50;
  padding-top: 60px;
  background-color: #2b2626;
}
</style>
