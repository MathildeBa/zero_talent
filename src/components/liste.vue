<template>
<div id="app">
    <ul>
    <li v-on:click='mathildeClick' style="color:red" v-if="color===true">{{ text }}</li>
    <li v-on:click='mathildeClick' style="color:yellow" v-else>{{ text }}</li>
    </ul>
</div>
</template>

<script>
//zeroTalents.vue
    export default {
        name: 'app',
        data(){
            return {
                color : true,
            } 
        },
        props:{
            text:String,
        },

        methods: {
            mathildeClick(){
                this.color=!this.color
                console.log(this.color)
            }
        }
    }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.red {
    color:yellow;
}
.yellow {
    color:red;
}
</style>
