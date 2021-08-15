<template>
  <div id="app">
    <pt/>
  </div>
</template>

<script>
import pt from './components/pt'

export default {
  name: 'App',
  components: {
    pt
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
