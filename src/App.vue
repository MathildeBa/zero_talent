<template>
  <div id="app">
    <zeroTalents></zeroTalents>
    <sousTitre></sousTitre>
    <liste v-for="(element, index) in liiste" :key="index" v-bind:text='element'></liste>
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
  },
  data(){
    return{
      liiste : ["Being On Time","Making An Effort","Being High Energy","Having A Positive Attitude","Being Passionate","Using Good Body Language","Being Coachable","Doing A Little Extra","Being Prepared","Having A Strong Work Ethic"],
    }
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
  margin-top: 20px;
}
</style>
