<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
    <MyComponent></MyComponent> 
    <MyComponent></MyComponent> <!--You can put your components as many times as you want-->
   
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import MyComponent from "./components/MyComponent.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
    MyComponent
  },
};
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

@import './assets/css/styles.css';
</style>
