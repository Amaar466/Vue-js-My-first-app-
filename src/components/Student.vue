<template>
    <h1>Props in Vue js 3</h1>
    <h2 >Student Name is : {{name}}</h2>
   
</template>


<script>

   export default{
    name:'Student',
    
    props:{
        name:String
    }
   

   }

</script>

<style scoped>
h1 {
 background-color:green;
 color:white;
 padding:5px;
}
</style>