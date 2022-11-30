<template>
  <div class="contact">
    <div class="container">
      <div class="text">
        <h3>Liên hệ</h3>
      </div>
      <div class="icons">
        <div class="icon left-icon">
          <a href="#"><img src="../assets/marker.png" alt="" /></a>
          <h3>Địa chỉ</h3>
          <p>Tân Bình - Tp.Hồ Chí Minh</p>
        </div>
        <div class="icon middle-icon">
          <a href="tel:+0968765936"><img src="../assets/phone.png" alt="" /></a>
          <h3>Điện thoại</h3>
          <p>0968765936</p>
        </div>
        <div class="icon right-icon">
          <a href="mailto:duc11102000@gmail.com"
            ><img src="../assets/mail.png" alt=""
          /></a>
          <h3>Email</h3>
          <p>duc11102000@gmail.com</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.container {
  width: 70%;
  margin: 0 auto;
  color: #d0d0d0;
  font-family: "noto sans";
}

.text h3 {
  font-size: 50px;
}
.icons {
  display: flex;
  justify-content: space-around;
}

.icon {
  box-shadow: inset 0 0 0 0 #ddb976;
  color: #d0d0d0;
  padding: 10px;
  transition: color 0.3s ease-in-out, box-shadow 0.3s ease-in-out;
  width: 190px;
  cursor: pointer;
}

.icon:hover {
  box-shadow: inset 210px 0 0 0 #ddb976;
  color: #000;
}
.icons .left-icon img {
  height: 6rem;
}

.icons .middle-icon img {
  height: 6rem;
}
.icons .right-icon img {
  height: 6rem;
}
</style>
