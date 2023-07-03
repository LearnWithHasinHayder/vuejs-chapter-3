<script setup>
const image = {
    src: 'https://images.unsplash.com/photo-1506744038136-46273834b3fb?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80',
    title: 'Water surrounded by trees and mountains',
    alt: 'Water surrounded by trees and mountains',
    link: 'https://unsplash.com/photos/NRQV-hBF10M',
}
</script>

<template>
    <section class="container mx-auto p-10">
        <h1 class="text-4xl mb-10 text-left">Data Project</h1>
        <section class="main flex space-x-4">
            <div class="flex space-y-4 flex-col w-1/2">
                <img v-bind="image">
                <h2 class="text-xl text-left"> {{ image.title }}</h2>
                <a target="_blank" :href="image.link" class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-3 px-4 rounded w-40 text-center">
                    Image Source
                </a>
            </div>
        </section>
    </section>
</template>

<style scoped></style>
