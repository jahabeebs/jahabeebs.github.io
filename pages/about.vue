<template>
    <div class="mx-screen">
        <div>
            <nav class="flex">
                <Navbar />
            </nav>
        </div>
        <div class="md:h-full h-screen w-screen bg-gradient-to-br from-blue-100 via-gray-200 to-blue-200 overflow-visible">
            <h1 class="flex text-2xl md:text-3xl pt-4 font-black justify-center"> Software Work Experience </h1>
            <p class="flex text-1xl md:text-2xl pt-4 md:pt-8 justify-center text-center text-blue-700 font-black"> Developer </p>
            <p class="flex text-1xl md:text-2xl justify-center text-center italic"> Kroger Technology</p>
            <p class="flex text-1xl md:text-2xl justify-center text-center"> October 2020 - Current</p>
            <h2 class="flex text-2xl md:text-3xl pt-4 md:pt-8 font-black justify-center"> Education </h2>
            <p class="flex text-1xl md:text-2xl pt-4 md:pt-8 justify-center text-center text-blue-700 font-black"> Java Development Bootcamp </p>
            <p class="flex text-1xl md:text-2xl justify-center text-center italic"> Tech Elevator</p>
            <p class="flex text-1xl md:text-2xl justify-center text-center"> July 2020 - October 2020</p>
            <p class="flex text-1xl md:text-2xl pt-4 md:pt-8 justify-center text-center text-blue-700 font-black"> Bachelor of Science in Public Health </p>
            <p class="flex text-1xl md:text-2xl justify-center text-center italic"> The Ohio State University</p>
            <p class="flex text-1xl md:text-2xl justify-center text-center"> August 2016 - May 2020</p>
            <h3 class="flex text-2xl md:text-3xl pt-4 md:pt-8 font-black justify-center"> My Developer Toolkit </h3>
            <p class="flex text-1xl md:text-2xl pt-4 md:pt-8 justify-center text-center text-blue-700 font-black"> Languages </p>
            <p class="flex text-1xl md:text-2xl justify-center text-center italic"> Java // JavaScript // SQL // CSS // HTML </p>
            <p class="flex text-1xl md:text-2xl pt-4 md:pt-8 justify-center text-center text-blue-700 font-black"> Frameworks </p>
            <p class="flex text-1xl md:text-2xl justify-center text-center italic"> Spring // Tailwind CSS // Vue.js // Nuxt.js </p>
            <p class="flex text-1xl md:text-2xl pt-4 md:pt-8 justify-center text-center text-blue-700 font-black"> CI/CD Tools </p>
            <p class="flex text-1xl md:text-2xl justify-center text-center italic md:pb-4"> Git // TeamCity // Jira</p>
        </div>
    </div>
</template>

<script>
import Navbar from '../components/Navbar.vue'
export default {
  components: { Navbar },}
</script>