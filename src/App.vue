<template>
  <HelloTest msg="toriqul"/>
  <HelloWorld msg="Welcome to Landing page"/>
  <ProDuct msg="Product section"/>
  <about msg="about"/>
 
</template>

<script>
import  HelloTest from './components/HelloTest.vue'
import HelloWorld from './components/HelloWorld.vue'
import ProDuct from '@/components/ProDuct'
import about from '@/components/about'

export default {
  name: 'App',
  components: {
    HelloWorld,
    HelloTest,
    ProDuct,
    about,
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
  margin-top: 60px;
}
</style>
