<template>
  <nav class="flex justify-center w-screen my-4">
  <div class="flex text-md md:text-lg space-x-3 md:space-x-12">
    <NuxtLink to="/" class="flex hover:text-blue-700">Home</NuxtLink>
    <NuxtLink to="/about" class="flex hover:text-blue-700">About</NuxtLink>
    <NuxtLink to="/projects" class="flex hover:text-blue-700">Projects</NuxtLink>
    <NuxtLink to="/blog" class="flex hover:text-blue-700">Blog</NuxtLink>
    <NuxtLink to="/contact" class="flex hover:text-blue-700">Contact</NuxtLink>
  </div>
</nav>
</template>

<script>
export default {
  name: "Navbar",
  computed: {
    currentRouteName() {
      return this.$route.name;
    }
  }
}
</script>
