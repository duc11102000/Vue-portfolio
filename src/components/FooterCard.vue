<template>
  <div class="footer">
    <div class="container">
      <div class="footer-1">
        <p>Cảm ơn mọi người đã bỏ thời gian xem qua portfolio của em.</p>
        <p>Trang portfolio này sẽ tiếp tục mở rộng theo thời gian :D</p>
      </div>
      <div class="footer-2">
        <p>2022. VueJS, HTML, CSS, Javascript. Code bởi Nguyễn Hữu Đức.</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.footer {
  height: 100px;
  margin-top: 100px;
  padding: 30px 0 100px 0;
  background: #ddb976;
  color: #2c3e50;
  font-family: 'noto sans';
}

.footer-1 {
  font-size: 30px;
  font-weight: bold;
  text-transform: uppercase;
}

.footer-1 p:nth-child(2) {
  font-size: 20px;
  font-weight: normal;
  text-transform: none;
}

@media (max-width: 768px) {
  .footer {
    margin-top: 80px;
  }
}
</style>
