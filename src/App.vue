<template>
  <div>
    <NavCard></NavCard>
    <ProfileCard></ProfileCard>
    <AboutCard></AboutCard>
    <ExperienceCard></ExperienceCard>
    <projects-card></projects-card>
    <ContactCard></ContactCard>
    <footer-card></footer-card>
  </div>
</template>

<script>
import NavCard from "./components/NavCard.vue";
import ProfileCard from "./components/ProfileCard.vue";
import AboutCard from "./components/AboutCard.vue"
import ExperienceCard from "./components/ExperienceCard.vue";
import ProjectsCard from "./components/ProjectsCard.vue";
import FooterCard from "./components/FooterCard.vue";
import ContactCard from "./components/ContactCard.vue";
export default {
  name: "App",
  components: {
    NavCard,
    ProfileCard,
    AboutCard,
    ExperienceCard,

    ProjectsCard,
    ContactCard,
    FooterCard,
  },
}
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600&display=swap");

body {
  margin: 0;
  font-family: "Poppins", sans-serif;
}

html {
  scroll-behavior: smooth;
}

section {
  padding-top: 4vh;
  /* height: 96vh; */
  margin: 0 10rem;
  box-sizing: border-box;
  min-height: fit-content;
}  

.section-container {
  display: flex;
}

.title {
  margin: 0;
  font-size: 3rem;
  text-align: center;
}

/*------------- ICONS -----------------*/

.icon {
  cursor: pointer;
  height: 2rem;
}

#app {
  /* font-family: Avenir, Helvetica, Arial, sans-serif; */
  /* text-align: center; */
  /* color: #2c3e50; */
  /* padding-top: 60px; */
  /* background-color: #2b2626; */
}


</style>
