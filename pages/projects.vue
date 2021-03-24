<template>
    <div class="mx-screen">
        <div>
            <nav class="flex">
                <Navbar />
            </nav>
        </div>
        <div class="h-screen w-screen bg-gradient-to-br from-blue-100 via-gray-200 to-blue-200 overflow-visible">
            <h1 class="flex text-2xl md:text-3xl pt-4 font-black justify-center"> Projects </h1>
            <p class="flex text-1xl md:text-2xl pt-4 md:pt-8 justify-center text-center text-blue-700 font-black"> My Website! </p>
            <p class="flex text-1xl md:text-2xl justify-center text-center"> Technologies Used:</p>
            <p class="flex text-1xl md:text-2xl justify-center text-center"> <a href="https://www.nuxtjs.org" class="hover:text-blue-700 italic"> Nuxt.JS&nbsp;//</a> <a href="https://www.tailwindcss.com" class="hover:text-blue-700 italic">&nbsp;Tailwind CSS&nbsp;//</a> <a href="https://pages.github.com/" class="hover:text-blue-700 italic">&nbsp;GitHub Pages </a></p>
            <p class="flex text-1xl md:text-2xl pt-4 md:pt-8 justify-center text-center text-blue-700 font-black"> Tech Elevator Projects </p>
            <p class="flex text-1xl md:text-2xl justify-center text-center"> <a href="https://github.com/jahabeebs/tech-elevator-grocery-capstone-backend" class="hover:text-blue-700 italic"> Grocery Store (Backend) </a> </p>
            <p class="flex text-1xl md:text-2xl justify-center text-center"> <a href="https://github.com/jahabeebs/tech-elevator-grocery-capstone-frontend" class="hover:text-blue-700 italic"> Grocery Store (Frontend) </a> </p>
            <p class="flex text-1xl md:text-2xl justify-center text-center"> <a href="https://github.com/jahabeebs/vendingmachine" class="hover:text-blue-700 italic"> Vending Machine CLI </a> </p>
            <p class="flex text-1xl md:text-2xl justify-center text-center"> <a href="https://github.com/jahabeebs/nationalparkcampsitereservation" class="hover:text-blue-700 italic"> National Park Reservation System </a> </p>
            <p class="flex text-1xl md:text-2xl justify-center text-center"> <a href="https://github.com/jahabeebs/TEnmo" class="hover:text-blue-700 italic"> P2P Payment System </a> </p>
        </div>
    </div>
</template>

<script>
import Navbar from '../components/Navbar.vue'
export default {
  components: { Navbar },}
</script>