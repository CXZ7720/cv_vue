<template>
  <div id="app">
    <img alt="logo" src="./assets/photo.jpg" width="200">
    <HelloWorld msg="Yeonggyun Kim"/>
  </div>
</template>

<script>
import HelloWorld from './components/content.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
@import url("https://fonts.googleapis.com/css?family=Noto+Sans+KR&display=swap");
@import url("https://maxcdn.bootstrapcdn.com/font-awesome/4.4.0/css/font-awesome.min.css");
@import url('https://fonts.googleapis.com/css?family=Raleway:400,700,800&display=swap');

#app {
  font-family: "Noto Sans KR", Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  width: 60%;
  color: #2c3e50;
  text-align: center;
  margin: 60px auto 5em;
}
  img {
    border-radius: 50%;
  }
</style>
