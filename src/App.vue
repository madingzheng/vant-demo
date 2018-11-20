<template>
  <div id="app">
    <Search/>
    <Pupup/>
  </div>
</template>
<script>
import Pupup from './components/Popup.vue'
import Search from './components/Search.vue'

export default {
  name: 'app',
  components: {
    Pupup,
    Search
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
}
</style>
