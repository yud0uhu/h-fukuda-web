<template>
  <CarouselView />
  <AppBar />
  <img alt="Vue logo" src="./assets/logo.png" />
  <HelloWorld msg="Welcome" />
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import CarouselView from "./components/CarouselView.vue";
import AppBar from "./components/AppBar.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
    CarouselView,
    AppBar,
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
</style>
