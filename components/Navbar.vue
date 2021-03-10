<template>
  <nav class="flex w-full justify-center py-3 md:py-4">
    <div class="flex text-md md:text-lg space-x-6 md:space-x-16">
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
