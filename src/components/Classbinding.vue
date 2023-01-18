<template>
    <h1 :class="applyStyle">Class Binding</h1>
    <button v-on:click="color =!color ">Apply style</button>
    <!--Text Show-->
    <br /><br />
    <div>
        <button v-on:click="showText = !showText">Toggle Text</button>
        <p v-if="showText">This text will show after clicking the button</p>
      </div>
    
</template>

<script>

   export default{
    name:'Classbinding',
    data()
    {
        return {
            color :'false',
            showText: false
        }
    },
    computed:{
        applyStyle(){
            return{
                orange:this.color,
                err:true,
            }
        }
    }

   }

</script>

<style>

.orange{
    background-color:blue;
    color:white;
    padding:5px;
}
.err
{
    color:red
}

</style>