<template>
  <div class="wrapper">
    <div class="main-container">
      <div class="container-one">
        <div class="profile">
          <img src="../assets/profile.png" alt="" />
          <h3>Nguyễn Hữu Đức</h3>
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
            Em tên là Nguyễn Hữu Đức, sinh viên của trường đại học
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
            <img src="../assets/sass.png" alt="" />
            <img src="../assets/js.png" alt="" />
            <img src="../assets/vuejs.png" alt="" />
            <img src="../assets/bootstrap.png" alt="" />
          </div>
        </div>
        <div class="button-container">
          <div class="cv-button">
            <a href="https://drive.google.com/file/d/1qY2Tsm9AC2jw5YUOKZUj0o86UGdCjVJT/view" target="_blank">My CV (VN)</a>
          </div>
          <div class="cv-button">
            <a href="https://drive.google.com/file/d/1tLqx0K9Yyn_-RZBIhuYi0ptuFe0OjUQa/view" target="_blank">My CV (EN)</a>
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
  background-color: #ddb976;
  border-radius: 25px;
  width: 70%;
  box-shadow: 0 20px 50px rgb(0 0 0 / 80%);
}

.container-one {
  background-color: #b68c47;
  color: #2c3e50;
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
  color: #2c3e50;
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

.about h1 {
  text-transform: uppercase;
}

.about p {
  font-size: 20px;
  font-family: 'noto sans';
  line-height: 35px;
}

.technology {
  margin-top: 70px
}

.technology h1 {
  font-size: 30px;
  font-weight: bold;
  text-transform: uppercase;
}
.logo {
  display: flex;
  justify-content: center;
  column-gap: 10px;
}

.logo img {
  height: 3.5rem;
  transition: 0.2s ease;
  cursor: pointer;
}

.logo img:hover {
  margin-top: -5px;
}

.button-container {
  margin-top: 5%;
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  column-gap: 20px;
}

.cv-button {
  background-color: #005ca4;
  margin: 5px;
  padding: 15px;
  border-radius: 15px;
  cursor: pointer;
  transition: 0.2s ease;
}

.cv-button:hover {
  opacity: 0.6;
}

.cv-button a {
  text-decoration: none;
  color: #fff;
}

@media only screen and (max-width: 950px) {
  .main-container {
    width: 95%;
  }
}

@media (max-width: 768px) {
  .about p {
    font-size: 16px;
  }

  .technology {
    margin-top: 40px;
  }
}
</style>
