<template>
  <div>
    <section id="experience">
      <p class="section__text__p1">Explore My</p>
      <h1 class="title">Experience</h1>
      <div class="experience-details-container">
        <div class="about-containers">
          <div class="details-container">
            <h2 class="experience-sub-title">Frontend Development</h2>
            <div class="article-container">
              <article>
                <img
                  src="../assets/checkmark.png"
                  alt="Experience icon"
                  class="icon"
                />
                <div>
                  <h3>HTML</h3>
                  <p>Intermediate</p>
                </div>
              </article>
              <article>
                <img
                  src="../assets/checkmark.png"
                  alt="Experience icon"
                  class="icon"
                />
                <div>
                  <h3>CSS</h3>
                  <p>Intermediate</p>
                </div>
              </article>
              <article>
                <img
                  src="../assets/checkmark.png"
                  alt="Experience icon"
                  class="icon"
                />
                <div>
                  <h3>SASS</h3>
                  <p>Experienced</p>
                </div>
              </article>
              <article>
                <img
                  src="../assets/checkmark.png"
                  alt="Experience icon"
                  class="icon"
                />
                <div>
                  <h3>JavaScript</h3>
                  <p>Intermediate</p>
                </div>
              </article>
              <article>
                <img
                  src="../assets/checkmark.png"
                  alt="Experience icon"
                  class="icon"
                />
                <div>
                  <h3>TypeScript</h3>
                  <p>Basic</p>
                </div>
              </article>
              <article>
                <img
                  src="../assets/checkmark.png"
                  alt="Experience icon"
                  class="icon"
                />
                <div>
                  <h3>Boostrap</h3>
                  <p>Experienced</p>
                </div>
              </article>
            </div>
          </div>
          <div class="details-container">
            <h2 class="experience-sub-title">Frontend Development</h2>
            <div class="article-container">
              <article>
                <img
                  src="../assets/checkmark.png"
                  alt="Experience icon"
                  class="icon"
                />
                <div>
                  <h3>Vue JS</h3>
                  <p>Intermediate</p>
                </div>
              </article>
              <article>
                <img
                  src="../assets/checkmark.png"
                  alt="Experience icon"
                  class="icon"
                />
                <div>
                  <h3>React JS</h3>
                  <p>Basic</p>
                </div>
              </article>
              <article>
                <img
                  src="../assets/checkmark.png"
                  alt="Experience icon"
                  class="icon"
                />
                <div>
                  <h3>Node JS</h3>
                  <p>Basic</p>
                </div>
              </article>
              <article>
                <img
                  src="../assets/checkmark.png"
                  alt="Experience icon"
                  class="icon"
                />
                <div>
                  <h3>Git</h3>
                  <p>Intermediate</p>
                </div>
              </article>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<style scoped>
#experience {
  position: relative;
  margin-top: 100px;
}

h3,
p {
  margin-top: 0;
  margin-bottom: 0;
}

p {
  color: rgb(85, 85, 85);
}

.section__text__p1 {
  color: rgb(85, 85, 85);
  text-align: center;
}

.experience-sub-title {
  color: rgb(85, 85, 85);
  font-weight: 600;
  font-size: 1.75rem;
  margin-bottom: 2rem;
}

.experience-details-container {
  display: flex;
  justify-content: center;
  flex-direction: column;
}

.article-container {
  display: flex;
  text-align: initial;
  flex-wrap: wrap;
  flex-direction: row;
  gap: 2.5rem;
  justify-content: space-around;
}

.about-containers {
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
}

article {
  display: flex;
  width: 10rem;
  /* justify-content: space-around; */
  gap: 0.5rem;
}

article div {
  margin-left: 10px;
}

article .icon {
  cursor: default;
}
</style>
