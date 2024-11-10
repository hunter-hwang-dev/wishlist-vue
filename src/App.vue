<template>
<WishList></WishList>
</template>

<script>
import WishList from "./components/WishList.vue"
export default { 
  name: "App",
  data() {
    return {
    }
  },
  components: {
    WishList
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
