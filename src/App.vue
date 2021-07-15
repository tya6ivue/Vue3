<template>
  <div id="app">
    <InputForm />
    
     <!-- <Assignment /> -->
  </div>
</template>

<script>

import InputForm from './components/InputForm.vue'
// import Assignment from './components/Assignment.vue'
export default {
  name: 'App',
  components: {
    InputForm,
    
    // Assignment
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
