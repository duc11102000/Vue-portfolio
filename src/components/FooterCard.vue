<template>
  <div class="footer">
    <footer>
      <nav>
        <div class="nav-links-container">
          <ul class="nav-links">
            <li><a href="#about">About</a></li>
            <li><a href="#experience">Experience</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#contact">Contact</a></li>
          </ul>
        </div>
      </nav>
      <p>2023 Vue.JS, HTML, CSS, Javascript.</p>
    </footer>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
footer {
  /* height: 26vh;
  margin: 0 1rem; */
  margin-top: 100px;
}

nav {
  display: flex;
  justify-content: space-around;
  align-items: center;
  height: 17vh;
}

a {
  color: black;
  text-decoration: none;
  text-decoration-color: white;
  transition: all 300ms ease;
}

a:hover {
  color: grey;
  text-decoration: underline;
  text-underline-offset: 1rem;
  text-decoration-color: rgb(181, 181, 181);
}
.nav-links {
  display: flex;
  gap: 2rem;
  list-style: none;
  font-size: 1.5rem;
}

footer p {
  text-align: center;
  color: rgb(85, 85, 85);
  margin-bottom: 20px;
}
</style>
