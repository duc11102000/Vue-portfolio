<template>
  <div class="title"><h1>Các project tiêu biểu</h1></div>
  <div class="main-container">
    <!-- {{ projectData.projectsArray }} -->
    <div
      class="project-card"
      v-for="(items, index) in projectData.projectsArray"
      :key="items"
    >
      <h2>{{ projectData.projectsArray[index].Title }}</h2>
      <img :src="projectData.projectsArray[index].Image" alt="" />
      <!-- ảnh thì dùng trang https://www.base64-image.de/ -->
      <p>{{ projectData.projectsArray[index].About }}</p>
      <div class="links">
        <a :href="projectData.projectsArray[index].Link1" target="_blank"
          ><img src="../assets/github.png" alt=""
        /></a>
        <a :href="projectData.projectsArray[index].Link2" target="_blank"
          ><img src="../assets/live.png" alt=""
        /></a>
      </div>
    </div>
  </div>
</template>

<script>
import jsonData from "../../projects.json";
// import carousel from 'vue-owl-carousel'

export default {
  // components: { carousel },

  data() {
    return {
      projectData: jsonData,
    };
  },
};
</script>

<style scoped>
.title {
  margin-top: 100px;
  margin-bottom: 50px;
}

.title h1 {
  color: #f5f5f5;
  text-transform: uppercase;
  font-size: 40px;
}
.main-container {
  /* margin-top: 5%; */
  display: grid;
  grid-template-columns: auto auto auto;
  grid-row-gap: 50px;
  width: 80%;
  margin: 0 auto;
}

.project-card {
  margin: 10px;
  padding: 10px;
  background-color: #fff;
  color: #2c3e50;
  border-radius: 25px;
  box-shadow: 0 20px 50px rgb(0 0 0 / 80%);
  width: 90%;
  cursor: pointer;
  transition: 0.2s ease;
}

.project-card:hover {
  transform: translateY(-20px);
  background-color: #ddb976;
}

.project-card img {
  height: 10rem;
}

.links {
  display: flex;
  justify-content: center;
  column-gap: 20px;
}
.links img {
  height: 2rem;
}

.links a {
  transition: 0.3s ease;
}
.links a:hover {
  opacity: 0.6;
}

@media screen and (min-width: 768px) and (max-width: 1024px) {
  .main-container {
    grid-template-columns: auto;
  }
}
</style>
