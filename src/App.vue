<template>
  <div id="app">
    <TestChart/>
  </div>
</template>

<script>
import TestChart from './components/TestChart'

export default {
  name: 'App',
  components: {
    TestChart
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
