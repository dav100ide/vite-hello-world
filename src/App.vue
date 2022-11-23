<script>
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';
export default {
   components: {
      AppTitle,
      AppHero,
   },
};
</script>

<template>
   <div class="container">
      <AppTitle />
      <AppHero />
   </div>
</template>

<style scoped>
.container {
   max-width: 1100px;
   margin: 0 auto;
}
</style>
