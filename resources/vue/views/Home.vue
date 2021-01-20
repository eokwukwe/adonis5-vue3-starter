<template>
  <div class="text-center">
    <h2 class="mb-4 text-xl">
      Welcome to
      <a
        href="https://preview.adonisjs.com/guides/quick-start"
        target="_blank"
        class="font-semibold text-blue-500 underline"
        >Adonis.js v5</a
      >
      with
      <a
        href="https://v3.vuejs.org/guide/introduction.html"
        target="_blank"
        class="font-semibold text-blue-500 underline"
        >Vue.js v3</a
      >
      using
      <a
        href="https://laravel-mix.com/"
        target="_blank"
        class="font-semibold text-blue-500 underline"
        >Laravel Mix</a
      >
    </h2>

    <p class="mb-5">
      Adapted from this article:
      <a
        href="https://dev.to/amirhoseinsalimi/integrate-vue-js-and-adonis-js-v5-using-laravel-mix-p0i"
        target="_blank"
        class="font-semibold text-blue-500 underline"
        >Integrate Vue.js and Adonis.js v5 using Laravel Mix</a
      >
    </p>

    <router-link
      class="px-2 py-1 text-xs text-gray-900 bg-gray-300 rounded hover:bg-gray-400"
      to="/about"
      >Go to About page</router-link
    >
  </div>
</template>

<script>
export default {
  name: 'Home',
}
</script>
