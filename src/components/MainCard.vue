<template>
  <div class="wrapper">
    <div class="main-container">
      <div class="container-one">
        <div class="profile">
          <img src="../assets/profile.png" alt="" />
          <h3>Name</h3>
          <p>Front-end developer</p>
        </div>
        <div class="social-links">
          <div class="link">
            <a href="https://github.com/duc11102000?tab=repositories" target="_blank">
              <img src="../assets/github.png" alt="" />
              <h2>Github</h2>
            </a>
          </div>
          <div class="link">
            <a href="">
              <img src="../assets/facebook.png" alt="" />
              <h2>Facebook</h2>
            </a>
          </div>
          <div class="link">
            <a href="">
              <img src="../assets/instagram.png" alt="" />
              <h2>Instagram</h2>
            </a>
          </div>
          <div class="link">
            <a href="">
              <img src="../assets/mail.png" alt="" />
              <h2>Gmail</h2>
            </a>
          </div>
        </div>
      </div>
      <div class="container-two">
        <div class="about">
          <h1>About me</h1>
          <p>
            Em tên là Nguyễn Hữu Đức, sinh viên năm cuối của trường đại học
            HUTECH. Với niềm đam mê và thích thú với các công nghệ liên quan
            front-end, em đã tích luỹ được kinh nghiệm sử dụng HTML, CSS,
            Javascript và framework VueJS để làm nên các project cá nhân. Với
            những gì em làm được thì em rất mong mình có được công việc lập
            trình viên front-end để có thể học hỏi được từ các bậc anh chị nhiều
            hơn. <br>
            Trang portfolio này của em sử dụng HTML, CSS và JS cùng với framework VueJS.
          </p>
        </div>
        <div class="technology">
          <h1>Technology Studied</h1>
          <div class="logo">
            <img src="../assets/html.png" alt="" />
            <img src="../assets/css.png" alt="" />
            <img src="../assets/js.png" alt="" />
          </div>
        </div>
        <div class="button-container">
          <div class="projects-button">
            <a href="">My projects</a>
          </div>
          <div class="projects-button">
            <a href="">My resume</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.wrapper {
  display: flex;
  justify-content: center;
}
img {
  height: 20px;
}

.main-container {
  display: flex;
  flex-direction: row;
  background-color: #a0d4ff;
  border-radius: 25px;
  width: 60%;
}

.container-one {
  background-color: #1292ee;
  width: 30%;
  padding: 2.5%;
  border-radius: 25px;
  box-shadow: rgba(0, 0, 0, 0.24) 0px 3px 8px;
}

.profile img {
  height: 8rem;
  border-radius: 20%;
}

.link a {
  text-decoration: none;
  color: #000;
  font-size: 12px;
}

.link img {
  height: 2rem;
}
.container-two {
  width: 70%;
  margin: 2.5%;
}

.about {
  text-align: left;
}

.about p {
  line-height: 25px;
}

.logo {
  display: flex;
  justify-content: center;
  column-gap: 10px;
}

.logo img {
  height: 3.5rem;
}

.button-container {
  margin-top: 5%;
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
}

.projects-button {
  background-color: #005ca4;
  margin: 5px;
  padding: 15px;
  border-radius: 15px;
  cursor: pointer;
  transition: 0.2s ease;
}

.projects-button:hover {
  opacity: 0.6;
}

.projects-button a {
  text-decoration: none;
  color: #fff;
}

@media only screen and (max-width: 950px) {
  .main-container {
    width: 95%;
  }
}
</style>
