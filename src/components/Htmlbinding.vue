<template>
    <h1>Html Binding</h1>
    <h2>{{text}}</h2>
    {{ tag }}
    <div v-html="tag"></div>
    <div v-html="tag2"></div>
</template>

<script>
export default{
    name:'Htmlbinding',
       
    data()
    {
        return {
            text:'amaar ul haq',
            tag:'<h2>Html Binding</h2>',
            tag2:'<h3>amaar@gmail.com</h3>'
        }
    }
}
</script>
<style scoped>
h1{
    background-color:red;
    color:white
}
</style>