<script setup>
const message = 'Welcome. Get ready to master Vue.js 3!'
const date = '30th June, 2023'
function getDate(){
  const date = new Date();
  return date.toDateString()
}
</script>

<template>
  <div class="container mx-auto flex items-center justify-center min-h-screen flex-col">
    <h1 class="text-4xl"> {{ message }} </h1>
    <h2 class="mt-10 text-xl text-gray-700">Today is <span>{{ getDate() }}</span></h2>
  </div>
</template>

<style scoped>

</style>
