<template>
  <div class="hobby">
    <div class="title">
      <h1>Hobby</h1>
    </div>
    <div class="container">
      <div class="hobby-card">
        <div class="face face-1">
          <div class="content">
            <img src="../assets/travel.png" alt="" />
            <h3>Du lịch</h3>
          </div>
        </div>
        <div class="face face-2">
          <div class="content">
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Minima et
              deserunt, harum explicabo dolor, quidem voluptates, dolore ab quae
              praesentium earum at est atque animi optio repellat nam sunt
              delectus!
            </p>
          </div>
        </div>
      </div>
      <div class="hobby-card">
        <div class="face face-1">
          <div class="content">
            <img src="../assets/console.png" alt="" />
            <h3>Video game</h3>
          </div>
        </div>
        <div class="face face-2">
          <div class="content">
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Minima et
              deserunt, harum explicabo dolor, quidem voluptates, dolore ab quae
              praesentium earum at est atque animi optio repellat nam sunt
              delectus!
            </p>
          </div>
        </div>
      </div>
      <div class="hobby-card">
        <div class="face face-1">
          <div class="content">
            <img src="../assets/code.png" alt="" />
            <h3>Code</h3>
          </div>
        </div>
        <div class="face face-2">
          <div class="content">
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Minima et
              deserunt, harum explicabo dolor, quidem voluptates, dolore ab quae
              praesentium earum at est atque animi optio repellat nam sunt
              delectus!
            </p>
          </div>
        </div>
      </div>
      <div class="hobby-card">
        <div class="face face-1">
          <div class="content">
            <img src="../assets/instrument.png" alt="" />
            <h3>Chơi nhạc cụ</h3>
          </div>
        </div>
        <div class="face face-2">
          <div class="content">
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Minima et
              deserunt, harum explicabo dolor, quidem voluptates, dolore ab quae
              praesentium earum at est atque animi optio repellat nam sunt
              delectus!
            </p>
          </div>
        </div>
      </div>
      <div class="hobby-card">
        <div class="face face-1">
          <div class="content">
            <img src="../assets/camera.png" alt="" />
            <h3>Nhiếp ảnh</h3>
          </div>
        </div>
        <div class="face face-2">
          <div class="content">
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Minima et
              deserunt, harum explicabo dolor, quidem voluptates, dolore ab quae
              praesentium earum at est atque animi optio repellat nam sunt
              delectus!
            </p>
          </div>
        </div>
      </div>
      <div class="hobby-card">
        <div class="face face-1">
          <div class="content">
            <img src="../assets/archery.png" alt="" />
            <h3>Bắn cung thể thao</h3>
          </div>
        </div>
        <div class="face face-2">
          <div class="content">
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Minima et
              deserunt, harum explicabo dolor, quidem voluptates, dolore ab quae
              praesentium earum at est atque animi optio repellat nam sunt
              delectus!
            </p>
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
.hobby {
  margin-top: 100px;
}

.hobby .title h1 {
  color: #d0d0d0;
  text-transform: uppercase;
  font-size: 40px;
}
.container {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  width: 80%;
  margin: 0 auto;
  position: relative;
  justify-content: space-between;
}
.content img {
  width: 100px;
  height: 100px;
}

.content h3 {
  color: #fff;
}

.container .hobby-card {
  position: relative;
  margin: 0 auto;
}

.container .hobby-card:hover {
  opacity: 1;
}
.container .hobby-card .face {
  width: 300px;
  height: 200px;
  transition: 0.5s;
}
.container .hobby-card .face.face-1 {
  position: relative;
  background-color: #333;
  display: flex;
  justify-content: center;
  align-items: center;
  z-index: 1;
  transform: translateY(100px);
  cursor: pointer;
}

.container .hobby-card:hover .face.face-1 {
  transform: translateY(0);
  background-color: #ddb976;
}
/* .container .hobby-card .face.face-1 .content {
  opacity: 0.2;
  transition: 0.5s;
} */

.container .hobby-card:hover .face.face-1 .content {
  opacity: 1;
}
.container .hobby-card .face.face-2 {
  position: relative;
  background-color: #fff;
  display: flex;
  justify-self: center;
  align-content: center;
  padding: 20px;
  box-sizing: border-box;
  box-shadow: 0 20px 50px rgba(0, 0, 0, 0.8);
  transform: translateY(-100px);
}

.container .hobby-card:hover .face.face-2 {
  transform: translateY(0);
}

@media(max-width: 768px) {
  .container {
    display: block;
    width: 40%;
    margin: 0 auto;
  }
}
</style>
