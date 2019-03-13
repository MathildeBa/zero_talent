<template>
  <div id="app">
    <zeroTalents></zeroTalents>
    <sousTitre></sousTitre>
    <liste></liste>
    
  </div>
</template>

<script>
import zeroTalents from './components/zeroTalents.vue';
import sousTitre from './components/sousTitre.vue';
import liste from './components/liste.vue'

export default {
  name: 'app',
  components: {
    zeroTalents,
    sousTitre,
    liste
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
