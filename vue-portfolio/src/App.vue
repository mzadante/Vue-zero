<template>
  <NavBar />
  <MainCard />
  <img alt="Vue logo" src="./assets/perfil.png">
</template>

<script>

import MainCard from './components/MainCard.vue';
import NavBar from './components/NavBar.vue'
export default {
  name: 'App',
  components: {
    MainCard,
    NavBar
  }
}
</script>

<style>
#app {
  display: flex;
  flex-direction: column;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
