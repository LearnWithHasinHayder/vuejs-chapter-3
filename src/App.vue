<script setup>
const number = 17
const animal = "Cow"
const pexels = 'https://www.pexels.com/search/' //https://www.pexels.com/search/Cow
</script>

<template>
  <div class="container mx-auto flex items-center justify-center min-h-screen flex-col">
      <h1 class="text-4xl">Welcome. Get ready to master Vue.js 3!</h1>
      <h2 class="mt-10 text-xl text-gray-700">{{ number }} divided by 4 = {{ number/4 }}</h2>
      <h2 class="mt-10 text-xl text-gray-700">{{ number }} is {{ number % 2==0? "Even":"Odd" }}</h2>
      <h2 class="mt-10 text-xl text-gray-700">
      <a target="_blank" :href='pexels+animal.toLowerCase()'>Search for {{ animal }}</a>
      </h2>
  </div>
</template>

<style scoped>

</style>
