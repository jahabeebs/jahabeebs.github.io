<template>
    <div class="container w-screen">
        <div>
            <nav class="flex">
                <Navbar />
            </nav>
        </div>
        <div class="h-screen w-screen bg-gradient-to-br from-blue-100 via-gray-200 to-blue-200 md:pl-32 overflow-auto">
            <h1 class="flex text-5xl pt-32 justify-center"> Coming Soon </h1>
        </div>
    </div>
</template>

<script>
import Navbar from '../components/Navbar.vue'
export default {
  components: { Navbar },}
</script>