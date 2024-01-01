<template>
  <div id="app">
    <HelloWorld msg="Personal Wiki"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
@font-face {
    font-family: Palatino;
    src: url('./assets/fonts/Palatino.ttf');
}
#app {
  font-family: Palatino;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
