<template>
  <Carousel :settings="settings" :breakpoints="breakpoints">
    <Slide class="single-hero-items set-bg" v-for="slide in 10" :key="slide" style="background-image: url('/img/hero-1.jpg')">
<!--      <div class="carousel__item" >{{ slide }}</div>-->
      <div>
        <p>Haloooo</p>
      </div>
    </Slide>

    <template #addons>
      <Pagination />
      <Navigation />
    </template>
  </Carousel>
</template>

<script>
import { defineComponent } from 'vue'
import 'vue3-carousel/dist/carousel.css'

import { Carousel, Navigation, Slide, Pagination } from 'vue3-carousel'
import 'vue3-carousel/carousel.css'
export default defineComponent({
  name: 'ExamplePagination',
  components: {
    Pagination,
    Carousel,
    Slide,
    Navigation,
  },
  data: () => ({
    // carousel settings
    settings: {
      itemsToShow: 1,
      snapAlign: 'center',
    },
    // breakpoints are mobile first
    // any settings not specified will fallback to the carousel settings
    breakpoints: {
      // 700px and up
      700: {
        itemsToShow: 3.5,
        snapAlign: 'center',
      },
      // 1024 and up
      1024: {
        itemsToShow: 5,
        snapAlign: 'start',
      },
    },
  }),
})
</script>