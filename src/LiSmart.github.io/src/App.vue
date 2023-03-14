<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <header>
    <img class="logo" src="./components/icons/logo.svg" width="200" height="200" />
    <div class="wrapper">
      <HelloWorld msg="Welcome to LeeSmart's Home!" />
    </div>
  </header>
</template>

<style scoped>
header {
  line-height: 1.5;
  text-align: center;
}

.logo {
  display: inline-block;
}
</style>
