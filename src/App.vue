<template>
  <div id="app">
    <operadorenviarmsg />
  </div>
</template>

<script>
import operadorenviarmsg from './components/operadorenviarmsg.vue'

export default {
  name: 'App',
  components: {
    operadorenviarmsg
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
</style>
