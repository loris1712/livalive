<template>
  <navbarDesktop></navbarDesktop>
  <homePart1></homePart1>
  <!--<img alt="Vue logo" src="./assets/logo.png" />
  <HelloWorld msg="Welcome to Your Vue.js App" />-->
</template>

<script>
import navbarDesktop from "./components/navbarDesktop.vue";
import homePart1 from "./components/homePart1.vue";

export default {
  name: "App",
  components: {
    navbarDesktop,
    homePart1,
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Heebo:wght@100;200;300;400;500;600;700;800;900&display=swap");

* {
  font-family: "Heebo", sans-serif;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
