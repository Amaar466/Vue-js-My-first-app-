<template>
    <!-- Mouse alert -->
<h1 v-on:mousemove="getConsole()"   style="background-color:aqua;color:white" >Event Click</h1>
<!-- with out parameter -->
<button v-on:click="test()">Click ME</button>
<!-- With parameter -->
<button v-on:click="getData()">Click ME</button>
<!-- <button v-on:click="getData('Button 2 Click')">Click ME</button> -->
<!-- Double Click action -->
<button v-on:dblclick="getData('Button double Click')">Click ME</button>
<h2>{{count}}</h2>
</template>
<script>
export default {
    Name:'Event',
    data()
    {
        return{
            count:0
        }
    },
    methods:{
        test()
        {
            alert("Function called");
        },
        getData()
        {
             this.count=this.count+1;
        },
        getConsole()
        {
            console.warn('Function Called');
        }

    }
}
</script>
<style>

</style>