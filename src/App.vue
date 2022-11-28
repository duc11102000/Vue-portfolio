<template>
  <div>
    <MainCard></MainCard>
    <projects-card></projects-card>
  </div>
</template>

<script>
import MainCard from './components/MainCard.vue'
import ProjectsCard from './components/ProjectsCard.vue';
export default {
  name: 'App',
  components: {
    MainCard,
    ProjectsCard,
  }
}
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
  background-color: #d6edff;
}
</style>
