<template>
  <div id="app">
    <img class="hero" alt="Vue logo" src="./assets/vue.png">
    <primoEsempio/>
  </div>
</template>

<script>
import primoEsempio from './components/primoEsempio.vue'

export default {
  name: 'App',
  components: {
    primoEsempio
  }
}
</script>

<style lang="scss">
#app 
{
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.title
{
  font-size: 30px;
  color: blue;
  background-color: yellow;
}
.hero
{
  width: 30%;
}
</style>
