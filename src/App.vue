<template>
  <div class="wish-background">
    <div>
      <h3
        class="fs-36 fw-500"
        style="text-align: left; line-height: 43px">
        누군가가 이미<br />이 선물을 보냈어요!
      </h3>
      <hr class="present-state-line" />
    </div>
    <h3 class="fs-36 fw-500">
      글라스락 렌지쿡
    </h3>
    <span class="fs-20 fw-500">탕, 찌개용</span
    >
    <img src="./assets/test.png" />
    <p class="fs-20 fw-300">
      냉장고에 넣어둔 찌개를 일반 그릇에다 넣고<br />
      데웠더니 전자레인지 안에서 터졌어요!<br />
      뚜껑이 있는 용기가 필요해요.
    </p>
    <hr class="price-tag-line" />
    <h4 class="fs-32 fw-500">₩14,900</h4>
  </div>
</template>

<script>
export default { 
  name: "App",
  components: {},
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
.wish-background {
  width: 412px;
  height: 917px;
  background: white;
  outline: solid 1px black;
}
.present-state-line {
  width: 377px;
  border-bottom: 1px solid black;
}
.price-tag-line {
  width: 187px;
  border-bottom: 1px solid black;
}
.fs-36 {
  font-size: 36px;
}
.fs-32 {
  font-size: 32px;
}
.fs-20 {
  font-size: 20px;
}
.fw-300 {
  font-weight: 500;
}
.fw-500 {
  font-weight: 500;
}
</style>
