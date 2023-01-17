<template>
    <h1>Pass data parent to Child</h1>
    <child name="Amaar ul haq" :user="user" :getData="getData"/>
  </template>
  
  <script>
  import Child from './Child.vue'
  
  export default {
    components: {
      Child
    },
    data() {
      return {
        user: {name:'hadi' , email:'hadi@gmail.com'}
      }
    },
    methods:
    {
        getData(){
            console.warn('parent to child');
            alert('Button Clicked');

        }
    }
  }
  </script>