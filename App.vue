<template>
  <div id="app">
    <img src="./assets/logo.png">
    <router-view/>
    <a href="page1.html">page1</a>
    <a href="page2.html">page2</a>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
