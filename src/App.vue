<template>
  <div id="app">
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <Plan msg="test"/>
  </div>
</template>

<script>
import Plan from './views/Plan.vue'

export default {
  name: 'App',
  components: {
    Plan
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
