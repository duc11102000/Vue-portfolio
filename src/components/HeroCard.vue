<template>
  <div class="hero">
    <div class="container">
      <div class="left-col">
        <h1>Xin chào</h1>
        <p>Em là Nguyễn Hữu Đức.</p>
        <p>Người có đam về và hứng thú với lập trình Front-end !!!</p>
        <p>Rất mong mọi người bỏ thời gian và xem xét portfolio của em ạ.</p>
        <!-- <a
          download="My CV.zip"
          href="../assets/My CV.zip"
          >Download CV</a
        > -->
      </div>
      <div class="right-col">
        <img src="../assets/developer.svg" alt="developer" />
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.hero {
  margin-bottom: 100px;
}
.hero .container {
  display: flex;
  justify-content: space-between;
  width: 70%;
  margin: 0 auto;
}

.left-col {
  text-align: left;
  display: flex;
  flex-direction: column;
  justify-content: center;
  color: #d0d0d0;
}

.left-col h1 {
  font-size: 60px;
  text-transform: uppercase;
}

.left-col p {
  font-family: "noto sans";
  font-size: 20px;
  line-height: 35px;
  width: 300px;
}
.right-col {
  width: 60%;
}
</style>
