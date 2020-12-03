<template>
  <div id="app">
    <loginsistema />
  </div>
</template>

<script>

/*import cliente-enviarmsg from './components/cliente-enviarmsg.vue'*/
import loginsistema from './components/loginsistema.vue' 

export default {
  name: 'App',
  components: {
    loginsistema
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
