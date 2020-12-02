<template>
  <div id="app">
    <!-- <ptcliente />-->
    <ptoperador />
  </div>
</template>

<script>
//import ptcliente from './components/ptcliente.vue'
import ptoperador from './components/ptoperador.vue'

export default {
  name: 'App',
  components: {
    //ptcliente,
    ptoperador
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
