<template>
  <div class="title-menu-wrapper">
    <TitleMenu />
    <div class="image-wrapper">
      <img src="@/assets/image/planet-earth.png">
    </div>
    <a-button type="primary">Регистрация</a-button>
  </div>
</template>

<script>
import TitleMenu from "@/components/main/TitleMenu";
export default {
  name: "MainMenu",
  components:{
    TitleMenu
  }
}
</script>

<style scoped>
  .title-menu-wrapper{
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    margin-bottom: 43px;
    align-items: center;
  }
  .image-wrapper{
    display: flex;
    justify-content: center;
  }
</style>
