<!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-JG0QQN6JWW"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-JG0QQN6JWW');
</script>
<template>
    <div class="mx-screen">
        <div>
            <nav class="flex">
                <Navbar />
            </nav>
        </div>
        <div class="h-screen w-screen bg-gradient-to-br from-blue-100 via-gray-200 to-blue-200 overflow-visible">
            <h1 class="flex text-5xl pt-32 justify-center"> Coming Soon </h1>
        </div>
    </div>
</template>

<script>
import Navbar from '../components/Navbar.vue'
export default {
  components: { Navbar },}
</script>