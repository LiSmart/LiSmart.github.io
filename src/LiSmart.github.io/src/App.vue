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
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}
</style>
