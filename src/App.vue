<template>
  <div id="app">
    
    <Vue1/>
    <Message/>
  </div>
</template>

<script>
import Vue1 from './components/Vue1.vue'
import Message from './components/Message'



export default {
  name: 'App',
   
  
  components: {
    Vue1,
    Message
   
  },
 
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
