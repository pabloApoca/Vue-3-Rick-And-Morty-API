<template>
  <!--<img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>-->
    <div>
    <h1>Rick and Morty</h1>
    <list-characters/>
  </div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import ListCharacters from '@/components/ListCharacters'
export default {
  name: 'App',
  components: {
    //HelloWorld
    ListCharacters
  }
}
</script>

<style lang="scss">
/*
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}*/
</style>
