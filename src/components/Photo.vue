<template>
    <!-- interpolation in Vue Js  -->
    <!-- {{}} -->
    <!-- check lenght  -->
    <h1>Photo Component {{"cricket".length}}</h1>
     <!-- use function with interpolation / parameter -->
     <h1 style="color:orange;">Company: {{getName('Conzummate')}}</h1>
    <!-- return any thing fron script to html  -->
    <h2>Email:  {{email}}</h2>
    <h1>Mobile:  {{mobile}}</h1>
    <h1>Mobile:  {{mobile==8888}}</h1>
   <!-- Use Method in Vue js -->
   <h1>Name2:  {{getName()}}</h1>
   
    

    
</template>

<script>

    export default {
        Name:'Photo',
        data()
        {
            return {
                email:'amaar@gmail.com',
                mobile:34885945,
                getName:function(a){
                    // return 'Conzummate Tech'
                      return a;
                
                },
                methods: {
                      getName: function() {
                        return 'Amaar';
                       
                }
  }
               

            }
        }
    }
</script>
<style scoped>
    h1{
        color:green;
    }
</style>