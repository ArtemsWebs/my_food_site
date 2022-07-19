<template>
    <MainMenu />
    <MainInfo />
</template>

<script>
import MainMenu from "@/components/main/MainMenu";
import MainInfo from "@/components/main/MainInfo";

export default {
  name: 'App',
  components: {
    MainMenu,
    MainInfo
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  margin-left: 20%;
  margin-right: 20%;
}
</style>
