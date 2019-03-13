<template>
  <div id="app">
    <zeroTalents></zeroTalents>
    
  </div>
</template>

<script>
import zeroTalents from './components/zeroTalents.vue';

export default {
  name: 'app',
  components: {
    zeroTalents
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
