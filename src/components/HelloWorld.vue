<template>
  <div class="hello">
<h1 style="background-color: brown;color: white;">Components in Vue Js</h1>
   
    <h3>{{ msg }}</h3>
    
  </div>
</template>

<script scoped>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
h3{
  color:red;
}
</style>
