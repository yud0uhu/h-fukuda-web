<template>
  <div>
    <AppBar />
  </div>
  <div style="width: 100%; position: absolute; top: 0">
    <CarouselView />
    <NewsImg img="a" class="mb-10" />
    <NewsImg img="a" class="mb-10" />
    <CistName />
    <FooterMenu />
    <NewsView />
  </div>
</template>

<script>
import CarouselView from "./components/CarouselView.vue";
import AppBar from "./components/AppBar.vue";
import NewsImg from "./components/NewsImg.vue";
import FooterMenu from "./components/FooterMenu.vue";
import CistName from "./components/CistName.vue";

export default {
  name: "TopPage",
  components: {
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
