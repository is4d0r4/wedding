<template>
  <img alt="casal" src="./assets/couple.jpg">
  
  <HelloWorld msg="Maciel e Isadora"/>
  <GiftList msg="Welcome to Your Vue.js App"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import GiftList from './components/GiftList.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    GiftList
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Dancing+Script:wght@400;600&family=Great+Vibes&display=swap');

#app {
  font-family:'Great Vibes', cursive;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #376367;
  margin: 0;
}

img{
  align-items: center;
  height: 8cm;
  width: auto;
}
</style>
