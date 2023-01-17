<template>
    <h1 v-if="show">If Condition</h1>
    <h1 v-else>else Condition</h1>
  <button v-on:click="show=!show">Toogle</button>
</template>

<script>
   export default {
    name:"Ifelsecondition",
    data()
    {
        return {
            show:true,
        }
    }
   }

</script>

