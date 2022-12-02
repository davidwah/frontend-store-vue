<template>
    <!-- Hero Section Begin -->
    <section class="hero-section">
      <carousel class="hero-items" :items="1" :autoplaySpeed="2000" :loop="true" :mouseDrag="true" :nav="false" :wrap-around="true">
  
        <div class="single-hero-items set-bg" style="background-image: url('/img/hero-1.jpg')">
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
        </div>
        <div class="single-hero-items set-bg" style="background-image: url('/img/hero-2.jpg')">
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
        </div>
        <!-- <template #addons>
          <Navigation />
          <Pagination />
        </template> -->
  
      </carousel>
    </section>
    <!-- Hero Section End -->
  </template>
  
  <script>
  import carousel from "vue-owl-carousel";
//   import 'vue3-carousel/dist/carousel.css'
  // import { Carousel, Slide, Pagination, Navigation } from 'vue3-carousel'
//   import { Carousel, Slide, Navigation, Pagination } from 'vue3-carousel'
  
  
  
  export default {
    name: "CarouselVue",
    components: {
        carousel,      
    },
  }
  </script>