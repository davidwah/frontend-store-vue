<template>
  <div class="home">
    <HeaderVue/>
    <CarouselVue/>
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderVue from '@/components/Header.vue';
import CarouselVue from '@/components/Carousel.vue';

export default {
  name: 'HomeView',
  components: {
    HeaderVue,
    CarouselVue,
    
  }
}
</script>
