<template>
  <!--<router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>-->
  <navbarDesktop></navbarDesktop>
  <router-view />
  <footerDesktop></footerDesktop>
</template>

<script>
import navbarDesktop from "./components/navbarDesktop.vue";
import footerDesktop from "./components/footerDesktop.vue";
export default {
  name: "App",
  components: {
    navbarDesktop,
    footerDesktop,
  },
};
</script>

<style scoped>
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
