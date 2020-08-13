<template>
  <!-- Baner Hero Begin -->
  <section class="hero-section" style="margin-top: -4vh">
    <carousel
      class="hero-items"
      :items="1"
      :nav="false"
      :loop="true"
      :autoplay="true"
      :dots="false"
      :autoplaySpeed="true"
    >
      <div class="single-hero-items set-bg" style="background-image: url('/img/q1@2x.png')">
        <div class="container">
          <div class="row">
            <div class="col-lg-5 text-white">
              <span style="color: #000000;">Bag</span>
              <h1 style="color: #000;">Ransel Holic</h1>
              <p>
                Spunbond adalah bahan kain yang digunakan untuk
                mengganti bahan plastik digunakan untuk kesehatan,
                dan bahan ini bersifat ramah lingkungan
              </p>
              <a href="#title-header" class="primary-btn">Shop Now</a>
            </div>
          </div>
        </div>
      </div>
      <div class="single-hero-items set-bg" style="background-image: url('/img/q9@2x.png')">
        <div class="container">
          <div class="row">
            <div class="col-lg-5 text-white">
              <span style="color: #000000;">Bag</span>
              <h1 style="color: #000000;">Shoes Holic</h1>
              <p>
                Tas khusus untuk menyimpan sepatu bola berbahan spunbound yang ramah lingkungan
                dengan bahan yang mudah terurai
              </p>
              <a href="#title-header" class="primary-btn">Shop Now</a>
            </div>
          </div>
        </div>
      </div>
    </carousel>

    <section class="title" id="title-header">
      <div class="row">
        <div class="col">
          <h3
            class="text-center"
            style="text-transform: uppercase; font-weight: 900; letter-spacing: 2px;"
          >Shop Styles By Fat</h3>
        </div>
      </div>
    </section>
  </section>
</template>

<script>
import carousel from "vue-owl-carousel";

export default {
  name: "BanerHero",
  components: {
    carousel
  }
};
</script>