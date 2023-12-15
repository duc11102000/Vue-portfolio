<!-- {{ projectData.projectsArray }} -->
<!-- ảnh thì dùng trang https://www.base64-image.de/ -->
<template>
  <div>
    <section id="projects">
      <p class="section__text__p1">Browse My Recent</p>
      <h1 class="title">Projects</h1>
      <swiper
        :options="swiperOptions"
        :slides-per-view="3"
        :space-between="30"
        :navigation="true"
        class="projects-details-container"
      >
        <swiper-slide
          v-for="(items, index) in projectData.projectsArray"
          :key="items"
        >
          <div class="details-container">
            <div class="article-container">
              <img
                :src="projectData.projectsArray[index].Image"
                alt="Project 1"
                class="project-img"
              />
            </div>
            <h2 class="experience-sub-title project-title">
              {{ projectData.projectsArray[index].Title }}
            </h2>
            <p>
              {{ projectData.projectsArray[index].About }}
            </p>
            <div class="btn-container">
              <a class="project-btn" :href="projectData.projectsArray[index].Link1" target="_blank"> Github </a>
              <a class="project-btn" :href="projectData.projectsArray[index].Link2" target="_blank"> Live Demo </a>
            </div>
          </div>
        </swiper-slide>
      </swiper>
    </section>
  </div>
</template>

<script>
import jsonData from "../../projects.json";
import { Swiper, SwiperSlide } from "swiper/vue";
import SwiperCore, { Navigation, Pagination } from "swiper/core";
import "swiper/css";
import "swiper/css/navigation";

SwiperCore.use([Navigation, Pagination]);

export default {
  components: {
    Swiper,
    SwiperSlide,
  },
  data() {
    return {
      projectData: jsonData,
      swiperOptions: {
        slidesPerView: 3,
        spaceBetween: 30,
        navigation: {
          nextEl: ".swiper-button-next",
          prevEl: ".swiper-button-prev",
        },
      },
    };
  },
};
</script>

<style scoped>
#projects {
  position: relative;
  margin-top: 100px;
}

.section__text__p1 {
  text-align: center;
}

.projects-details-container {
  margin-top: 40px;
}

.projects-containers {
  display: flex;
  gap: 2rem;
  margin-bottom: 2rem;
  margin-top: 2rem;
}
.details-container {
  padding: 1.5rem;
  flex: 1;
  background: white;
  border-radius: 2rem;
  border: rgb(53, 53, 53) 0.1rem solid;
  border-color: rgb(163, 163, 163);
  text-align: center;
  height: 400px;
  cursor: pointer;
}

.details-container p {
  text-align: left;
}

.project-img {
  border-radius: 2rem;
  width: 90%;
  height: 90%;
}

.project-title {
  color: black;
}

.btn-container {
  display: flex;
  justify-content: center;
  gap: 1rem;
}

.project-btn {
  text-decoration: none;
  border: 2px solid #a3a3a3;
  font-weight: 600;
  transition: all 300ms ease;
  padding: 1rem;
  width: 8rem;
  border-radius: 2rem;
  color: black;
  background: none;
}

.project-btn:hover {
  cursor: pointer;
  background: rgb(53, 53, 53);
  color: white;
  border: rgb(255, 255, 255) 0.1rem solid;
}
</style>
