<script setup>
const message = "Welcome. Get ready to master Vue.js 3 with Ostad"
const date = new Date()
const dateString = date.toLocaleString()

function getDate(){
  return "11th July, 2023"
}

const number = 16

const person = {
  fname:"Jane",
  lname:"Doe",
  getName(){
    return this.fname + " " + this.lname
  }
}
</script>

<template>
  <div class="container mx-auto flex items-center justify-center min-h-screen flex-col">
      <h1 class="text-4xl">{{ message }}</h1>
      <!-- <h2 class="mt-10 text-xl text-gray-700">name of the person is {{ person.getName() }} </h2> -->
      <h2 class="mt-10 text-xl text-gray-700">{{ number }} is</h2>
  </div>
</template>

<style scoped>

</style>
