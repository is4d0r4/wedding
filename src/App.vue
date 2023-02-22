<template>
  <NavBar />
  <HelloWorld msg="Maciel e Isadora"/>
  <GiftList />

</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import GiftList from './components/GiftList.vue'
import NavBar from './components/NavBar.vue';

export default {
  name: 'App',
  components: {
    HelloWorld,
    GiftList,
    NavBar
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
}

img{
  align-items: center;
  height: 8cm;
  width: auto;
}
</style>
