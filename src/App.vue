<template>
  <div id="app">
    <home/>
  </div>
</template>

<script>
import Home from './components/Home.vue'

export default {
  name: 'App',
  components: {
    Home
  }
}
</script>

<style>
* {
  margin: 0;
  padding: 0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  width: 100vw;
  background-color: #fffbb6;
}
.container {
  width: 100vw;
}
div, ul {
  box-sizing: border-box;
}
li {
  list-style: none;
}
</style>
