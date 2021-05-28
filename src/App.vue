<template>
  <div id="app">
    
    <Title/>
 
    <Hero/>
    
   
  </div>
</template>

<script>
import Title from './components/Title.vue'
import Hero from './components/Hero.vue'

export default {
  name: 'App',
  components: {
    Title,
    Hero
  }
}
</script>

<style lang="scss">

*{
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
  
  height: 100vh;
  background-color: black;
  
}


</style>
