<template>
  <div id="app">
    <SheetDisplay />
  </div>
</template>

<script>
import SheetDisplay from './components/SheetDisplay.vue'

export default {
  name: 'App',
  components: {
    SheetDisplay
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
