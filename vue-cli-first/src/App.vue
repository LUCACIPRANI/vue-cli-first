<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <hr>
    <Jumbotron msg="Welcome to the Jumbotron"/>
    <img alt="Vue logo" src="./assets/camera.jpeg">
    <hr>
    <Footer messagge="This is a footer"/>
    <img alt="Vue logo" src="./assets/footer.png">
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Jumbotron from './components/Jumbotron.vue'
import Footer from './components/Footer.vue'


export default {
  name: 'App',
  components: {
    HelloWorld,
    Jumbotron,
    Footer
  }
}
</script>

<style lang="scss">
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: white;
  background-image: url("https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSKFcfc3lLfpbn8A5tdeEJ1htvfSaduvEn1Lg&usqp=CAU");
}
</style>
