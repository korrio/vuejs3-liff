<template>
  <div id="app">
    <img alt="Vue logo" src="https://hackth.line.me/wp-content/themes/Conference_Pro/logo2020.png">
    <HelloWorld msg="LINE HACK 2020"/>
  </div>
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
  body {
    background:#252525;
  }
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #efefef;
  margin-top: 60px;
}
</style>
