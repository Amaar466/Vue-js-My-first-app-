<template>
  <div class="hello">
<h1>Components</h1>
    <h2>Vue Js 3</h2>
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
