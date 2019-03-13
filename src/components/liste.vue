<template>
<div id="app">
    <ul>
    <li v-for="(stuff, index) in liste" :key="index">{{ stuff }}</li>
    </ul>
</div>
</template>

<script>
//zeroTalents.vue
    export default {
    name: 'app',
    data(){
        return {
            liste : ["Being On Time","Making An Effort","Being High Energy","Having A Positive Attitude","Being Passionate","Using Good Body Language","Being Coachable","Doing A Little Extra","Being Prepared","Having A Strong Work Ethic"]
        } 
        }
    }

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
