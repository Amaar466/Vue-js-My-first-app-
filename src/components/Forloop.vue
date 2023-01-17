<template>
 <h1>For Loop and List </h1>
        <ul>
            <!-- <li v-for="item in items">{{ item }}</li> -->
            <li v-for="item in technology" :key="item">
                {{item }}
            </li>
        </ul>

        <br /><br />
        <ul>
            <li v-for="item in user" :key="item.email">
                Name is :{{ item.name }} and email is :{{ item.email }}
            </li>
        </ul>
</template>
  
<script>
export default {
    data() {
        return {
            // items: ['Java', 'PHP', 'Laravel']
            technology: ['Java', 'PHP', 'Laravel'],
            user:[{
                name:'Amaar',
                email:'Amaar@gmail.com',
            },
            {
                name:'amir',
                email:'Amir@gmail.com',
            },
            {
                name:'bilal',
                email:'bilal@gmail.com',
            },
            
        ]
        }
    }
}
</script>
  
<style scoped>
h1 {
    background-color: green;
    color: white;
}
</style>