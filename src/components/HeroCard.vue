<template>
  <div class="hero">
    <div class="container">
      <div class="left-col">
        <h1>Xin chào</h1>
        <p>Em là Nguyễn Hữu Đức.</p>
        <p>Người có đam về và hứng thú với lập trình Front-end!!!</p>
        <p>Rất mong mọi người bỏ chút thời gian và xem qua portfolio của em ạ.</p>
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
  margin-bottom: 110px;
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

@media (max-width: 768px) {
  .hero {
    margin-bottom: 50px;
  }
  .hero .container {
    width: 95%;
  }

  .left-col h1 {
    font-size: 40px;
  }

  .left-col p {
    font-size: 18px;
  }

  .right-col {
    width: 50%;
  }
}
</style>
