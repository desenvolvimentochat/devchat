<template>
  <div id="app">
    <operadorhistoricomsg />
  </div>
</template>

<script>

/*import cliente-enviarmsg from './components/cliente-enviarmsg.vue'*/
import operadorhistoricomsg from './components/operadorhistoricomsg.vue' 

export default {
  name: 'App',
  components: {
    operadorhistoricomsg
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
