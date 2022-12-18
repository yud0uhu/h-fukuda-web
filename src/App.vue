<template>
  <AppBar />
  <CarouselView />
  <NewsImg img="a" class="mb-10" />
  <NewsImg img="a" class="mb-10" />
  <CistName />
  <FooterMenu />
</template>

<script>
//import HelloWorld from "./components/HelloWorld.vue";
import CarouselView from "./components/CarouselView.vue";
import AppBar from "./components/AppBar.vue";
import NewsImg from "./components/NewsImg.vue";
import FooterMenu from "./components/FooterMenu.vue";
import CistName from "./components/CistName.vue";

export default {
  name: "App",
  components: {
    // HelloWorld,
    CarouselView,
    AppBar,
    NewsImg,
    CistName,
    FooterMenu,
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
