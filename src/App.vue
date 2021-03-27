<template>
  <img class = "image" alt="My Picture" src="./assets/20200905_085628.jpg" height="300">
  <ResComp/>
  <HelloWorld msg="I am an International Student from Pakistan, Double Majoring in Computer Science and Economics at Knox College. I am interested in Full Stack Web and Mobile development and currently looking for Software Engineering Internships"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import ResComp from './components/ResComp.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    ResComp
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

.image {
  float: right;
  display: inline;
}

.resume {
  float: left;
  right:20%;
  display: inline;
}

.hello {
  position: sticky;
}
</style>
