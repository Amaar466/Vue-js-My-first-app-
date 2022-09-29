<template>
    <h1>Get Input Value</h1>
    <input type="text"  placeholder="Enter Email"  v-model="email"/>
    <br /><br />
    <input type="password" placeholder="Enter Password" v-model="password"/>
    <br /><br />
    <button v-on:click="getData()" type="button">Get Value</button>
</template>
<script>
    export default {
        Name:'Getinput',
        data()
        {
            return {
                email:null,
                password:null,
            }
        },
        methods:
        {
          getData()
          {
            console.warn('Values:',this.email,this.password);
          }
        }
    }
</script>