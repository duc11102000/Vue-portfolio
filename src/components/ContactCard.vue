<template>
  <div>
    <section id="contact">
      <p class="section__text__p1">Get in Touch</p>
      <h1 class="title">Contact Me</h1>
      <div class="contact-info-upper-container">
        <div class="contact-info-container">
          <img
            src="../assets/email.png"
            alt="email icon"
            class="icon contact-icon email-icon"
          />
          <p>
            <a href="mailto:duc11102000@gmail.com">duc11102000@gmail.com</a>
          </p>
        </div>
        <div class="contact-info-container">
          <img
            src="../assets/phone2.png"
            alt="phone icon"
            class="icon contact-icon"
          />
          <p><a href="tel:0968765936">0968765936</a></p>
        </div>
      </div>
      <a href="#desktop-nav" class="backtotop"
        ><img src="../assets/arrow.png" alt="Arrow icon" class="icon arrow"
      /></a>
    </section>
  </div>
</template>
<script>
export default {
  methods: {
    scrollToTop() {
      window.scrollTo(0, 0);
    },
  },
};
</script>

<style scoped>
#contact {
  position: relative;
  display: flex;
  justify-content: center;
  flex-direction: column;
  margin-top: 150px;
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

.section__text__p1 {
  text-align: center;
}
.contact-info-upper-container {
  display: flex;
  justify-content: center;
  border-radius: 2rem;
  border: rgb(53, 53, 53) 0.1rem solid;
  border-color: rgb(163, 163, 163);
  margin: 2rem auto;
  padding: 0.5rem;
}

.contact-info-container {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 0.5rem;
  margin: 1rem;
}

.contact-info-container p {
  font-size: larger;
}

.contact-icon {
  cursor: default;
}

.email-icon {
  height: 2.5rem;
}

.backtotop {
  position: absolute;
  right: 0;
  bottom: 0;
}

.backtotop img {
  transform: rotate(180deg);
}

</style>
