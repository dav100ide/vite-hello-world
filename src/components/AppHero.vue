<script>
export default {
   data() {
      return {
         content: 'jumbotron',
      };
   },
};
</script>

<template>
   <div>
      {{ content }}
   </div>
</template>

<style scoped>
div {
   background: blue;

   text-align: center;
   padding: 1rem;
}
</style>
