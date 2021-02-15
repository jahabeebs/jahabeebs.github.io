<template>
    <div class="container w-screen">
        <div>
            <nav class="flex">
                <Navbar />
            </nav>
        </div>
        <div class="h-screen w-screen bg-gradient-to-br from-blue-100 via-gray-200 to-blue-200 md:pl-32 overflow-auto">
            <div class="flex flex-col justify-center">
            <h1 class="flex font-black md:mr-48 md:text-4xl text-2xl pt-20 justify-center">Email Me!</h1>
            <a class="flex justify-center md: mt-2 md:mr-48 md:h-12 h-10 hover:opacity-50" href="mailto: habib.50@osu.edu">
            <img alt="Button to email Jacob Habib" src="~/assets/envelope-line.svg" />
            </a>
            </div>
        </div>
    </div>
</template>

<script>
import Navbar from '../components/Navbar.vue'
export default {
  components: { Navbar },}
</script>