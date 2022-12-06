<template>
  <div class="home">
    <HeaderDWP/>
    <HeroDWP/>
    <!-- <ExamplePagination/> -->

  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import HeaderDWP from '@/components/HeaderDWP.vue';
import HeroDWP from "@/components/HeroDWP.vue";
// import ExamplePagination from "@/components/ExamplePagination";

export default {
  name: 'HomeView',
  components: {
    HeaderDWP,
    HeroDWP,
    // ExamplePagination
  },

}
</script>
