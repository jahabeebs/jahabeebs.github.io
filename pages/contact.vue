<template>
    <div class="container w-screen">
        <div>
            <nav class="flex">
                <Navbar />
            </nav>
        </div>
        <div class="h-screen w-screen bg-gradient-to-br from-blue-100 via-gray-200 to-blue-200 md:pl-32 overflow-auto">
            <div class="flex md:mr-40 pt-4 justify-center">
            <iframe src="https://docs.google.com/forms/d/e/1FAIpQLSf2d-CwqajTEOYZo0fW5jeINPkNtw81bIQC2yINSJ9uv5YWtw/viewform?embedded=true" width="640" height="820" frameborder="0" marginheight="0" marginwidth="0">Loading…</iframe>
            </div>
        </div>
    </div>
</template>

<script>
import Navbar from '../components/Navbar.vue'
export default {
  components: { Navbar },}
</script>