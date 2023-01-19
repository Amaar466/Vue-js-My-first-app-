<template>
    <h1>Ref in vue js</h1>
    <input type="text" ref="input" />
    <button v-on:click="getData()">Clicked me</button>
</template>

<script>
export default
    {
        name: 'Ref',
        methods: {
            getData() {
                this.$refs.input.focus();
                this.$refs.input.style.color='green';
                let val=this.$refs.input.value;
                alert(val);
            }
        }
    }

</script>