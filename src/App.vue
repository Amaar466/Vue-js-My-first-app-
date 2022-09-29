<template>
<img alt="Vue logo" src="./assets/logo.png">
<HelloWorld msg="Welcome to My First Vue.js App" />
<Photo />
<Cricket />
<Method />
<Event />
<Bindingtwoway />
<Getinput />
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Photo from './components/Photo.vue';
import Cricket from './components/Cricket.vue';
import Method from './components/Method.vue';
import Event from './components/Event.vue';
import Bindingtwoway from './components/bindingtwoway.vue';
import Getinput from './components/Getinput.vue';




export default {
    name: 'App',
    components: {
    HelloWorld,
    Photo,
    Cricket,
    Method,
    Event,
    Bindingtwoway,
    Getinput
}
}
</script>

<style>
#app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
}

</style>
