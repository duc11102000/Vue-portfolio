<template>
  <div>
    <section id="about">
      <p class="section__text__p1">Get To Know More</p>
      <h1 class="title">About Me</h1>
      <div class="section-container">
        <div class="about-details-container">
          <div class="about-containers">
            <div class="details-container">
              <img
                src="../assets/experience.png"
                alt="Experience icon"
                class="icon"
              />
              <h3>Experience</h3>
              <p>6+ months <br />Frontend Development</p>
            </div>
            <div class="details-container">
              <img
                src="../assets/education.png"
                alt="Education icon"
                class="icon"
              />
              <h3>Education</h3>
              <p>HUTECH University</p>
            </div>
          </div>
          <div class="text-container">
            <p>
              Hi, I'm <strong>Nguyễn Hữu Đức</strong>, i'm from the
              <strong>HUTECH University</strong>, major in
              <strong>Software Engineer. </strong>. I have a profound
              passion for <strong>Front-End Technology</strong>, and I love to create beautiful
              and performant products with delightful user experiences.
              Proficient in <strong>HTML</strong>, <strong>CSS</strong>, and
              <strong>Javascript</strong>, along with expertise in the
              <strong>Vue.JS</strong> framework, i am looking forward to be a
              professional <strong>Front-end Developer</strong> in a highly productive work
              environment.
            </p>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<style scoped>
#about {
  position: relative;
  margin-top: 50px;
}

p {
  color: rgb(85, 85, 85);
  margin: 0;
  padding: 0;
}
.about-containers {
  gap: 2rem;
  margin-bottom: 2rem;
  margin-top: 2rem;
}

.about-details-container {
  width: 800px;
  margin: 0 auto;
  justify-content: center;
  flex-direction: column;
}

.about-containers,
.about-details-container {
  display: flex;
}

.about-pic {
  border-radius: 2rem;
}

.arrow {
  position: absolute;
  right: -5rem;
  bottom: 2.5rem;
}

.details-container {
  padding: 1.5rem;
  flex: 1;
  background: white;
  border-radius: 2rem;
  border: rgb(53, 53, 53) 0.1rem solid;
  border-color: rgb(163, 163, 163);
  text-align: center;
}

.section-container {
  gap: 4rem;
  height: 80%;
}

.section__pic-container {
  height: 400px;
  width: 400px;
  margin: auto 0;
}

.section__text__p1 {
  text-align: center;
}

.section__text__p2 {
  font-size: 1.75rem;
  margin-bottom: 1rem;
  color: rgb(85, 85, 85);
}

@media screen and (max-width: 1400px) {
  .about-containers {
    flex-wrap: wrap;
  }
}

/* @media screen and (max-width: 1200px) {
  .about-containers {
    margin-top: 0;
  }
}

@media screen and (max-width: 600px) {

  .about-containers,
  .contact-info-upper-container,
  .btn-container {
    flex-wrap: wrap;
  }
}  */
</style>
