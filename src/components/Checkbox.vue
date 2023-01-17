<template>

    <h1>Get Checbox and Radio button</h1>
    <h3>Technology</h3>
    <label for="java">Java</label>
    <input type="checkbox" value="java" v-model="technology" id="java">

    <label for="php">Php</label>
    <input type="checkbox" value="php" v-model="technology" id="php">

    <label for="java">Laravel</label>
    <input type="checkbox" value="Laravel" v-model="technology" id="Laravel">

    <br /><br />
    <h3>Who i am</h3>
    <label for="student">Student</label>
    <input type="radio" value="student" v-model="who" name="who" id="student">

    <label for="developer">Developer</label>
    <input type="radio" value="developer" v-model="who" name="who"  id="developer">


    <h4>Selected Technology  {{ technology }}</h4>
    <h4>I am A : {{ who }}</h4>
</template>

<script>
   export default {
    name:"Checkbox",
    data()
    {
        return {
            technology:[],
            who:[]
        }
    }
   }

</script>

<style scoped>
h1{
    background-color:blue;
    color:white;
}
</style>