<template>
    <div class="mx-screen">
        <div>
            <nav class="flex">
                <Navbar />
            </nav>
        </div>
        <div class="h-screen w-screen bg-gradient-to-br from-blue-100 via-gray-200 to-blue-200 overflow-visible">
            <h1 class="flex text-2xl md:text-3xl pt-4 font-black justify-center"> Software Work Experience </h1>
            <h2 class="flex text-1xl md:text-2xl pt-4 md:pt-8 justify-center text-center"> Developer <br> October 2020 - Current</h2>
            <div class="flex justify-center">
                <img class="flex object-contain w-20 md:w-40 mt-2" alt="Logo for Kroger Technology" src="~/assets/kroger-tech.png" />
            </div>
        </div>
    </div>
</template>

<script>
import Navbar from '../components/Navbar.vue'
export default {
  components: { Navbar },}
</script>