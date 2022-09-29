<template>
    <h1 style="background-color:blue;color: white;">Methods in Vue Js</h1>
    <!-- <h2>Email:{{email}}</h2> -->
    <h2>Name:{{getName('bakar')}}</h2>
    <h2>All Data:{{getData()}}</h2>
</template>
<script>


export default {
    Name:'Method',
    data(){
      return {
        Name:'ammar',
          email: 'aliAmaar@gmail.com',
      }
    },
    methods:{
        getName(Name){
            // return 'bilal'
            return Name;
        },
        getData(){
            return {
                Name:this.Name,
                email:this.email
            }
        }
    }
   
}
</script>
<style>


</style>