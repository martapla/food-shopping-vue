<script setup>
import { RouterView } from 'vue-router';
import ShoppingHeader from './components/ShoppingHeader.vue';
</script>

<template>
  <div>
     <ShoppingHeader />
     <RouterView />
  </div>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Rubik:wght@300;400;500;700&display=swap');

* {
font-family: 'Rubik', sans-serif;
margin:0;
padding:0;
box-sizing:border-box;
}

.container {
  max-width:1100px;
  margin: 0 auto;
}

</style>