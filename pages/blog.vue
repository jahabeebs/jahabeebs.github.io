<template>
    <div>
        <div>
            <nav class="flex">
                <Navbar />
            </nav>
        </div>
        <div class="h-screen w-screen bg-gradient-to-br from-blue-100 via-gray-200 to-blue-200 overflow-visible">
          <h1 class="flex text-2xl md:text-3xl pt-4 font-black justify-center"> Posts </h1>
          <p

            class="flex text-1xl md:text-2xl pt-4 md:pt-8 justify-center text-center text-blue-700 font-black hover:text-blue-900 italic">
            <a href="https://jahabeebs.hashnode.dev/building-a-serverless-stock-price-web-app-with-cloudflare-workers-pages-workers-kv-and-cron-triggers"> Building a Serverless Stock Price Web App With Cloudflare Workers, Pages, Workers KV and Cron Triggers </a></p>
          <p

            class="flex text-1xl md:text-2xl pt-4 md:pt-8 justify-center text-center text-blue-700 font-black hover:text-blue-900 italic">
            <a href="https://mirror.xyz/beebs.eth/56q-KiMQe_fe1UMrCzyusNxiB-ZLyfKuUJUrZ9102IE"> My 5-Step Approach to Problem Solving as a Junior Developer</a></p>
          <p
            class="flex text-1xl md:text-2xl pt-4 md:pt-8 justify-center text-center text-blue-700 font-black hover:text-blue-900 italic">
            <a href="https://jahabeebs.hashnode.dev/creating-a-free-jamstack-website-with-nuxtjs-tailwind-css-and-github-pages"> Creating a free JAMstack website with Nuxt.js, Tailwind CSS, and GitHub Pages </a></p>
        </div>
    </div>
</template>

<script>
import Navbar from '../components/Navbar.vue'
export default {
  components: { Navbar },}
</script>
