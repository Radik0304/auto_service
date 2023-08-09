<template>
  <div class="home__container">
    <MainBlocK/>
    <AchievementsBlock/>
  </div>
</template>

<script>
import MainBlocK from '@/components/MainBlock.vue'
import AchievementsBlock from '@/components/AchievementsBlock.vue';

export default {
  name: 'HomeView',
  components: {
    MainBlocK,
    AchievementsBlock
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
