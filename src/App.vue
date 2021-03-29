<template>
  <div class="main">
  </div>
  <img class = "image" alt="My Picture" src="./assets/20200905_085628.jpg" height="400">
  <HelloWorld msg="I am an International Student from Pakistan, Double Majoring in Computer Science and Economics at Knox College. I am interested in Full Stack Web and Mobile development and currently looking for Software Engineering Internships"/>
  <SocialMedia/>
  <ResComp/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import ResComp from './components/ResComp.vue'
import SocialMedia from './components/SocialMedia.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    ResComp,
    SocialMedia
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #f1f8ff;
  margin-top: 60px;
}
*{
  position: relative;
}
img{
  margin: 5px;
  padding: 20px;
  width: 400px;
  border-radius: 50%;
  border: #818588;
}
body{
  background-image: url('./assets/background.jpg');
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
  background-repeat: no-repeat;
  background-attachment: fixed;
}
.main{
  background-color: #000000;
  width: 80%;
  height: 100%;
  margin: 0 10%;
  opacity: 0.5;
  position: absolute;
}

</style>
