<template>
  <div class="container w-screen">
    <div>
      <nav class="flex">
        <Navbar />
      </nav>
    </div>
    <div class="h-screen w-screen bg-gradient-to-br from-blue-100 via-gray-200 to-blue-200 md:pl-32 overflow-auto">
        <div class="flex items-center space-x-4 md:space-x-24 pt-8">
          <div class="flex flex-col">
            <div class="flex text-5xl md:text-5xl font-black text-blue-700"> Hello! <br> </div>
            <h1 class="flex md:text-5xl text-2xl font-black"> &nbsp; My name is Jacob Habib <br> &nbsp; &nbsp; I'm a Developer <br> &nbsp; &nbsp; &nbsp; Based in Cincinnati, Ohio </h1>
          </div>
          <div class="flex flex-col">
            <img alt="LinkedIn headshot for Jacob Habib" class="flex rounded-lg md:max-w-xs" src="~/assets/headshot.jpg" />
            <div class="flex h-10 ml-16 mt-2 space-x-2 md:justify-center">
              <a class="flex w-10 hover:opacity-50" href="https://linkedin.com/in/jacob-habib/">
              <img alt="Button to LinkedIn profile for Jacob Habib" src="~/assets/linkedin-square-color.svg" />
              </a>
              <a class="flex hover:opacity-50" href="mailto: habib.50@osu.edu">
              <img alt="Button to email Jacob Habib" src="~/assets/envelope-line.svg" />
              </a>
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
