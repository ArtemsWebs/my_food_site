<template>
  <div class="info-wrapper">
    <div class="info-wrapper__topContent">
    <img class="info-wrapper__leaves" src="@/assets/image/leaves.svg"/>
      <div class="info-wrapper__text">
        <a-typography-title>Organic Fruit & Vegetables</a-typography-title>
        <a-typography-title>Приколы</a-typography-title>
      </div>
    </div>
    <div class="info-wrapper__lowContent">
      <img src="@/assets/image/fructs-vegatables.svg"/>
    </div>
  </div>
</template>

<script>
export default {
  name: "MainInfo",
}
</script>

<style scoped>
.info-wrapper{
  background: #F3FBF8;
}
.info-wrapper__leaves{
  position: relative;
  right: 27%;
}
.info-wrapper__text{
  position: relative;
  bottom: 300px;
}
</style>
