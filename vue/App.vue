<template>
  <div id="app">
    <nav-bar class="nalu"></nav-bar>
    <side-bar class="menu"></side-bar>
    <img alt="Vue logo" src="./assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import NavBar from "./components/NavBar.vue";
import SideBar from "./components/SideBar";
export default {
  name: "App",
  components: {
    HelloWorld,
    NavBar,
    SideBar
  }
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 10px;
  font-size: 14px;
  list-style: 26px;
  .nalu {
    text-align: left;
    color: white;
  }
  .menu {
    color: white;
  }
}
</style>
