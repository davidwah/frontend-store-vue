<template>
  <div class="home">
    <HeaderDWP/>
    <HeroDWP/>

  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import HeaderDWP from '@/components/HeaderDWP.vue'
import HeroDWP from "@/components/HeroDWP";

export default {
  name: 'HomeView',
  components: {
    HeaderDWP,
    // eslint-disable-next-line vue/no-unused-components
    HeroDWP
  }
}
</script>
