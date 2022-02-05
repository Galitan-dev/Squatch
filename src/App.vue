<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  --flame: #f1592aff;
  --wheat: #ead2acff;
  --gainsboro: #d1dedeff;
  --rich-black-fogra-29: #0d1b2aff;
  --oxford-blue: #1b263bff;
  
  background-color: var(--rich-black-fogra-29);
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: var(--gainsboro);
  margin-top: 60px;
}
</style>
