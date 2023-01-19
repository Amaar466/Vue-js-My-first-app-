<template>
    <div>
      <button @click="sendData">Send Data</button>
    </div>
  </template>
  
  <script>
  export default {
    methods: {
      sendData() {
        this.$emit('sendData', 'Hello from child')
      }
    }
  }
  </script>