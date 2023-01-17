<template>
    <h1>Reuse Components</h1>
  <ul>
    <li v-for=" item in users" :key="item.name">

        <User :data="item" :getData="getData"/>
        <!-- {{ item.name }}
        {{ item.email }} -->
    </li>
  </ul>
    
</template>

<script>
import User from './User.vue'
export default {
    Name: 'Reuse',
    components: {
        User
    },
    methods:{
        getData(name)
        {
            alert(name);
        }
    },
    data() {
        return {
       users:[
            {name: 'amaar', email: 'amaar@gmail.com' },
            { name: 'bilal', email: 'bilal@gmail.com' },
            { name: 'hadi', email: 'hadi@gmail.com' },
            { name: 'ali', email: 'ali@gmail.com' },
        ],
            }
    }
}
</script>