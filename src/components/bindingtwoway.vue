import { count } from 'console';
<template>
    <h1  style="background-color:brown;color:white">Two Way Binding</h1>
    <input type="text" v-model="count" />
    <h2>{{count}}</h2>
</template>
<script>


    export default {
        Name:'Bindingtwoway',
        data()
        {
            return{
            count:10000
        }
        }
    }
</script>