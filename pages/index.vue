<template>
  <div class="mx-screen">
      <nav class="flex">
        <!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-JG0QQN6JWW"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-JG0QQN6JWW');
</script>
        <Navbar />
      </nav>
    <div class="flex justify-center items-start h-screen md:pt-8 pt-4 bg-gradient-to-br from-blue-100 via-gray-200 to-blue-200">
        <div class="flex md:items-center space-x-4 md:space-x-24">
          <div class="flex flex-col ml-2">
            <div class="flex text-2xl md:text-6xl font-black text-blue-700 pr-32"> Hello! </div>
            <h1 class="flex text-2xl md:text-5xl font-black text-justify-center"> &nbsp; My name is Jacob Habib <br> &nbsp; &nbsp; I'm a Developer <br> &nbsp; &nbsp; &nbsp; Based in Cincinnati, Ohio</h1>
          </div>
          <div class="flex flex-col">
            <img alt="LinkedIn headshot for Jacob Habib" class="flex rounded-lg md:w-80 md:max-w-xs mr-2" src="~/assets/headshot.jpg" />
            <div class="flex h-6 ml-8 space-x-2 mt-1 md:h-12 md:mt-2 md:space-x-2 md:justify-center">
              <a class="flex w-16 hover:opacity-50" href="https://linkedin.com/in/jacob-habib/">
              <img alt="Button to LinkedIn profile for Jacob Habib" src="~/assets/linkedin-square-color.svg" />
              </a>
              <NuxtLink to="/contact" class="flex hover:opacity-50">
              <img alt="Button to email Jacob Habib" src="~/assets/envelope-line.svg" />
              </NuxtLink>
            </div>
          </div>
        </div>
    </div>
  </div>
</template>

<script>
import Navbar from '../components/Navbar.vue'
export default {
  components: { Navbar },}
</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS
.container {
@apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/

.title {
  font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  display: flex;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
