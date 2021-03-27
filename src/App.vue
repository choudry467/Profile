<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <Resume pdf="public/ChoudryAbdulRehmanResume.pdf"/>
  <HelloWorld msg="Welcome"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Resume from './components/Resume.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Resume
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
