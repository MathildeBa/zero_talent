<template>
<div id="app">
  <h2 > {{title1}} </h2>
  <h1>{{title2}}</h1>
  <ul>
    <li v-for="(elements, index) in liste" :key="index">{{ elements }}</li>
  </ul>
</div>
</template>

<script>
  //zeroTalents.vue
    export default {
      name: 'app',
      data(){
        return {
          title1 : '10 THINGS THAT REQUIRE',
          title2 : 'ZERO TALENT',
          liste : ["Being On Time","Making An Effort","Being High Energy","Having A Positive Attitude","Being Passionate","Using Good Body Language","Being Coachable","Doing A Little Extra","Being Prepared","Having A Strong Work Ethic"]
        } 
      }
    }

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
