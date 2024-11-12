<template>
  <WishList></WishList>

  <p>{{ myData }}</p>
</template>

<script>
import WishList from "./components/WishList.vue";
import myData from "./assets/data.js";

export default {
  name: "App",
  data() {
    return {
      myData,
    };
  },
  components: {
    WishList,
  },
};
</script>

<style>
@import url("https://cdn.jsdelivr.net/gh/orioncactus/pretendard@v1.3.9/dist/web/variable/pretendardvariable-dynamic-subset.min.css");
#app {
  font-family: "Pretendard Variable", sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  line-height: 120%;
  color: #000000;
}
</style>
