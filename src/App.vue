<script setup>
// export default {
//   data(){
//     const message = "Welcome. Get ready to master Vue.js 3 with Ostad"
//     const date = "10th July, 2023"
//     return {
//       message, date
//     }
//   },
//   methods:{
//     getDate(){
//       return "11th July"
//     }
//   }
// }
// export default {
//   setup(){
//     const message = "Welcome. Get ready to master Vue.js 3 with Ostad"
//     const date = "10th July, 2023"

//     function getDate(){
//       return "11th July, 2024"
//     }

//     return {
//       message, date, getDate
//     }
//   }
// }

const message = "Welcome. Get ready to master Vue.js 3 with Ostad"
const date = "<strong>10th July, 2023</strong>"


function getDate() {
  return "11th July, 2024"
}

function evenOrOdd(n) {
  if (n % 2 == 0) {
    return "Even"
  }
  return "Odd"
}
const number = 16
</script>

<template>
  <div class="container mx-auto flex items-center justify-center min-h-screen flex-col">
    <h1 class="text-4xl">{{ message }}</h1>
    <!-- <h2 class="mt-10 text-xl text-gray-700">Today is <span> {{ getDate() }}</span></h2> -->
    <!-- <h2 class="mt-10 text-xl text-gray-700">{{ number }} is {{ evenOrOdd(number) }}</h2> -->
    <h2 class="mt-10 text-xl text-gray-700">{{ number }} is {{ number % 2 == 0 ? "Even" : "Odd" }}</h2>
  </div>
</template>

<style scoped></style>
