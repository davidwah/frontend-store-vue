<template>
  <div class="home">
    <HeaderVue/>
    <CarouselVue/>
    <ItemsVue/>
    <InstaVue/>
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderVue from '@/components/Header.vue';
import CarouselVue from '@/components/Carousel.vue';
import ItemsVue from '@/components/Items.vue';
import InstaVue from '@/components/Insta.vue';


export default {
  name: 'HomeView',
  components: {
    HeaderVue,
    CarouselVue,
    ItemsVue,
    InstaVue
  }
}
</script>
