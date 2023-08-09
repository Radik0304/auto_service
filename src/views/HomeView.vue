<template>
  <div class="home__container">
    <MainBlocK/>
  </div>
</template>

<script>
// @ is an alias to /src
import MainBlocK from '@/components/MainBlock.vue'

export default {
  name: 'HomeView',
  components: {
    MainBlocK
  }
}
</script>

<style scoped>
.home__container {
  border: 1px solid black;
  width: 100%;
  height: 100%;
}
</style>
