<template>
  <div id="app">
    <img src="./assets/logo.png">
    <!-- <HelloWorld/> -->
    <Hello />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld'
import Hello from './components/Hello'

export default {
  name: 'App',
  components: {
    Hello,
    // HelloWorld,
  }
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
