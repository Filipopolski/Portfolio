<template>
  <section id="facts" class="facts">
    <div class="container">

      <div class="section-title">
        <h2>
          Facts
          ::after
        </h2>
        <p>
          Magnam dolores commodi suscipit. Necessitatibus eius consequatur ex aliquid fuga eum quidem. Sit sint
          consectetur velit. Quisquam quos quisquam cupiditate. Et nemo qui impedit suscipit alias ea. Quia fugiat sit
          in iste officiis commodi quidem hic quas.
        </p>
      </div>

      <div class="row no-gutters">

        <div class="col-lg-3 col-md-6 d-md-flex align-items-md-stretch aos-init aos-animate" data-aos="fade-up">
          <div class="count-box">
            <i class="icofont-simple-smile">
              ::before
            </i>
            <span data-toggle="counter-up">232</span>
            <p><strong>Happy Clients</strong> consequuntur quae</p>
          </div>
        </div>

        <div class="col-lg-3 col-md-6 d-md-flex align-items-md-stretch aos-init aos-animate" data-aos="fade-up"
             data-aos-delay="100">
          <div class="count-box">
            <i class="icofont-document-folder">
              ::before
            </i>
            <span data-toggle="counter-up">521</span>
            <p><strong>Projects</strong> adipisci atque cum quia aut</p>
          </div>
        </div>

        <div class="col-lg-3 col-md-6 d-md-flex align-items-md-stretch aos-init aos-animate" data-aos="fade-up"
             data-aos-delay="200">
          <div class="count-box">
            <i class="icofont-live-support">
              ::before
            </i>
            <span data-toggle="counter-up">1,463</span>
            <p><strong>Hours Of Support</strong> aut commodi quaerat</p>
          </div>
        </div>

        <div class="col-lg-3 col-md-6 d-md-flex align-items-md-stretch aos-init aos-animate" data-aos="fade-up"
             data-aos-delay="300">
          <div class="count-box">
            <i class="icofont-users-alt-5">
              ::before
            </i>
            <span data-toggle="counter-up">15</span>
            <p><strong>Hard Workers</strong> rerum asperiores dolor</p>
          </div>
        </div>

      </div>

    </div>
  </section>
</template>

<script>
    export default {
        name: "facts-section"
    }
</script>

<style scoped>

  .facts {
    padding-bottom: 30px;
  }

  .facts .count-box {
    padding: 30px;
    width: 100%;
  }

  .facts .count-box i {
    display: block;
    font-size: 44px;
    color: #149ddd;
    float: left;
  }

  .facts .count-box span {
    font-size: 48px;
    line-height: 40px;
    display: block;
    font-weight: 700;
    color: #050d18;
    margin-left: 60px;
  }

  .facts .count-box p {
    padding: 15px 0 0 0;
    margin: 0 0 0 60px;
    font-family: "Raleway", sans-serif;
    font-size: 14px;
    color: #122f57;
  }

  .facts .count-box a {
    font-weight: 600;
    display: block;
    margin-top: 20px;
    color: #122f57;
    font-size: 15px;
    font-family: "Poppins", sans-serif;
    transition: ease-in-out 0.3s;
  }

  .facts .count-box a:hover {
    color: #1f5297;
  }

</style>
