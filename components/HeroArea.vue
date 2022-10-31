<template>
  <!-- Welcome Area Start -->
  <section class="hero-area sky-blue d-flex align-items-center">
    <div class="container">
      <div class="row align-items-center">
        <div class="col-lg-6 col-md-12">
          <!-- Start Hero Caption -->
          <div class="hero-caption">
            <span class="subheading">Hey! We are</span>
            <h1>Unycode !</h1>
            <div>
              A team of
              <div id="typed-strings">
              <!-- Animated Text Writer -->
              <span>Freelancers.</span>
              <span>Web Designers.</span>
              <span>Web Developers.</span>
              <span>Data Analysts.</span>
              <span>Consultants.</span>
            </div>
            <span class="LR-C" id="typed" style="white-space:pre;"></span>
            </div>
            <p>
              To create a valuable and seamless solution for all our clients.
            </p>
<!--            <a href="#" class="btn radius-btn">Download</a>-->
          </div>
          <!-- End Hero Caption -->
        </div>
        <div class="col-lg-6 d-none d-lg-block">
          <!-- Hero Right Image -->
          <div class="hero-img">
            <img src="assets/img/hero/hero.png" alt="Hero image" />
          </div>
        </div>
      </div>
    </div>

    <!-- Hero Animated Shape -->
    <div class="hero-shape custom-animation">
      <img src="assets/img/hero/hero-shape.png" alt="animation shape" />
    </div>
  </section>
  <!-- Welcome Area End -->
</template>

<script>
export default {
  name: "HeroArea"
};
</script>
