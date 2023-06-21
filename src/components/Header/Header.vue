<script setup>
import { RouterLink } from 'vue-router';

</script>

<template>
    <header class="">
        <nav class="flex justify-between h-20 items-center px-3 border-2 border-b-gray-700 bg-gray-500">
            <div class="flex md:flex md:flex-grow flex-grow justify-end space-x-4 mr-10">
                <RouterLink to="/" class="py-4 px-2 text-white font-semibold hover:text-teal-500 transition duration-300">Home</RouterLink>
                <RouterLink to="/blogs" class="py-4 px-2 text-white font-semibold hover:text-teal-500 transition duration-300">Blog</RouterLink>
                <RouterLink to="/Work" class="py-4 px-2 text-white font-semibold hover:text-teal-500 transition duration-300">Aboute</RouterLink>
                <RouterLink to="/contact" class="py-4 px-2 text-white font-semibold hover:text-teal-500 transition duration-300">Contact</RouterLink>
            </div>
        </nav>
    </header>
</template>

<style lang="scss" scoped>
.router-link-exact-active {
    background-color: white;
    border: 1px solid white;
    border-radius: 15px;
    color: black;
    padding: auto;
  }
</style>