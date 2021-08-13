<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <MyfirstVue msg="My First Vue Project" />
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import MyfirstVue from './components/myFirstVue.vue';

export default {
  name: 'App',
  components: {
    HelloWorld,
    MyfirstVue
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
