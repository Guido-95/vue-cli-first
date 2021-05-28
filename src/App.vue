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

body {
  background-color: rgba(0, 0, 0, 0.8);
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
  width: 100%;
  margin-top: 40px;
}


</style>
