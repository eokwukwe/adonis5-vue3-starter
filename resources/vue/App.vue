<template>
  <span class="flex items-center justify-center h-screen">
    <router-view></router-view>
  </span>
</template>

<script>
export default {
  name: 'App',

  mounted() {
    console.log('App has been mounted!!!')
  },
}
</script>

<style>
  
</style>