<template>
    <h1>{{ name }}</h1>
    <h2>{{user.name}}</h2>
    <button v-on:click="getData()">Function Called</button>
  </template>
  
  <script>
  export default {
    props:{
        name:String,
        user:Object,
        getData:Function
    }
  }
  </script>