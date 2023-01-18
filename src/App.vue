<template>
<img alt="Vue logo" src="./assets/logo.png">
<HelloWorld msg="Welcome to My First Vue.js App" />
<Photo />
<Cricket />
<Method />
<Event />
<Bindingtwoway />
<Getinput />
<Checkbox />
<Ifelsecondition />
<Forloop />
<Parent />
<Reuse />
<Htmlbinding />
<Classbinding />
<!-- <User /> -->

</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Photo from './components/Photo.vue';
import Cricket from './components/Cricket.vue';
import Method from './components/Method.vue';
import Event from './components/Event.vue';
import Bindingtwoway from './components/bindingtwoway.vue';
import Getinput from './components/Getinput.vue';
import Checkbox from './components/Checkbox.vue';
import Ifelsecondition from './components/Ifelsecondition.vue';
import Forloop from './components/Forloop.vue';
import Parent from './components/Parent.vue';
import Child from './components/Child.vue';
import Reuse from './components/Reuse.vue';
import Htmlbinding from './components/Htmlbinding.vue';
import Classbinding from './components/Classbinding.vue';
// import User from './components/User.vue';




export default {
    name: 'App',
    components: {
    HelloWorld,
    Photo,
    Cricket,
    Method,
    Event,
    Bindingtwoway,
    Getinput,
    Checkbox,
    Ifelsecondition,
    Forloop,
    Parent,
    Child,
    Reuse,
    Htmlbinding,
    Classbinding
    // User

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
