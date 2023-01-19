<template>
  <h1>Parent1 Componenet</h1>
    <div>
      <child1 @sendData="getData"></child1>
    </div>
    <Child1 />
  </template>
  
  <script>
  import Child1 from './Child1.vue'
  
  export default {
    components: {
      Child1
    },
    methods: {
      getData(data) {
        alert(data)
      }
    }
  }
  </script>