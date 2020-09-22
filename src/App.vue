<template>
  <div > 
    <Header/>
    <Pbf/> 
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Pbf from './components/Pbf.vue' 

export default {
  name: '#app',
  components: {
    Header, 
    Pbf
   
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
}
</style>
