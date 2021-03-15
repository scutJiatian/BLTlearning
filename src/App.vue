<template>
  <div id="app">
  
    <Echarts />
  </div>
</template>

<script>

import Echarts from './components/echarts.vue'

export default {
  name: 'App',
  components: {
    Echarts
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
