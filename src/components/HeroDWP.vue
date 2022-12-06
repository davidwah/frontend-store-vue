<template>
  <!-- Hero Section Begin -->
  <section class="hero-section">
    <Carousel class="hero-items" :itemsToShow="1" :autoplay="5000" :wrap-around="true">
      <Slide class="single-hero-items set-bg" style="background-image: url('/img/hero-1.jpg')">
        <div class="container">
          <div class="row">
            <div class="col-lg-5">
             <span>Bag,kids</span>
              <h1>Black friday</h1>
              <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore</p>
              <a href="#" class="primary-btn">Shop Now</a>
            </div>
          </div>
        </div>
      </Slide>
      <template #addons>
        <Navigation />
        <Pagination />
      </template>

    </Carousel>
  </section>
  <!-- Hero Section End -->
</template>

<script>
// import carousel from "vue-owl-carousel";
import 'vue3-carousel/dist/carousel.css'
// import style from '../../public/css/owl.carousel.min.css'
// import style from '../../public/css/style.css'
// import { Carousel, Slide, Pagination, Navigation } from 'vue3-carousel'
import { Carousel, Slide, Navigation, Pagination } from 'vue3-carousel'



export default {
  name: "HeroDWP",
  components: {
    Carousel,
    Slide,
    Pagination,
    Navigation,
  },
}
</script>
<style>
@import url();
</style>