<template>
  <div class="main-container">
    <!-- {{ projectData.projectsArray }} -->
    <div class="project-card" v-for="(items, index) in projectData.projectsArray" :key="items">
        <h2>{{ projectData.projectsArray[index].Title }}</h2>
        <img :src="projectData.projectsArray[index].Image" alt="">
        <p>{{ projectData.projectsArray[index].About }}</p>
        <div class="links">
            <a :href="projectData.projectsArray[index].Link1" target="_blank"><img src="../assets/github.png" alt=""></a>
            <!-- <a :href="projectData.projectsArray[index].Link2" target="_blank"><img src="../assets/github.png" alt=""></a> -->
        </div>
    </div>
  </div>
</template>

<script>
import jsonData from "../../projects.json"
export default {
    data() {
        return {
            projectData: jsonData
        }
    }
}
</script>

<style scoped>
    .main-container {
        margin-top: 5%;
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
        /* flex-wrap: wrap; */
    }

    .project-card {
        margin: 10px;
        padding: 10px;
        /* flex-wrap: 0 0 20%; */
        background-color: #fff;
        border-radius: 25px;
        box-shadow: rgba(0, 0, 0, 0.24) 0px 3px 8px;
        width: 37%;
    }

    .project-card img {
        height: 10rem;
    }

    .links img {
        height: 2rem;
    }
</style>