<script setup>
  import {RouterView} from 'vue-router';
  import QuizesView from './views/QuizesView.vue'
</script>

<template>
  <div class="conatiner">
    <RouterView />
  </div>
</template>

<style scoped>
 .container {
    max-width: 100px;
    margin: 0 auto;
  }
</style>