<template>
  <div id="app">
    <HelloNuxt />
  </div>
</template>

<script>
import HelloNuxt from './components/HelloNuxt.vue'

export default {
  name: 'App',
  components: {
    HelloNuxt
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
