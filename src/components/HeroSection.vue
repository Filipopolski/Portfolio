<template>
  <section id="hero" class="d-flex flex-column justify-content-center align-items-center">
    ::before
    <div class="hero-container aos-init aos-animate" data-aos="fade-in">
      <h1>Alex Smith</h1>
      <p>
        "I'm"
        <span class="typed" data-typed-items="Designer, Developer, Freelancer, Photographer">Developer</span>
        <span class="typed-cursor typed-cursor--blink">|</span>
      </p>
    </div>
  </section>
</template>

<script>
    export default {
        name: "Hero-section"
    }
</script>

<style scoped>

  #hero {
    width: 100%;
    height: 100vh;
    /*background: url("../img/hero-bg.jpg") top center;*/
    background-size: cover;
  }

  #hero:before {
    content: "";
    background: rgba(5, 13, 24, 0.3);
    position: absolute;
    bottom: 0;
    top: 0;
    left: 0;
    right: 0;
    z-index: 1;
  }

  #hero .hero-container {
    position: relative;
    z-index: 2;
    min-width: 300px;
  }

  #hero h1 {
    margin: 0 0 10px 0;
    font-size: 64px;
    font-weight: 700;
    line-height: 56px;
    color: #fff;
  }

  #hero p {
    color: #fff;
    margin-bottom: 50px;
    font-size: 26px;
    font-family: "Poppins", sans-serif;
  }

  #hero p span {
    color: #fff;
    padding-bottom: 4px;
    letter-spacing: 1px;
    border-bottom: 3px solid #149ddd;
  }

  @media (min-width: 1024px) {
    #hero {
      background-attachment: fixed;
    }
  }

  @media (max-width: 768px) {
    #hero h1 {
      font-size: 28px;
      line-height: 36px;
    }
    #hero h2 {
      font-size: 18px;
      line-height: 24px;
      margin-bottom: 30px;
    }
  }

</style>
