<template>
  <a-menu v-model:selectedKeys="current" mode="horizontal">
    <a-menu-item key="about">
      <template #icon>
        <mail-outlined />
      </template>
      О нас
    </a-menu-item>
    <a-menu-item key="menu">
      <template #icon>
        <mail-outlined />
      </template>
      Меню
    </a-menu-item>
    <a-menu-item key="contacts">
      <template #icon>
        <mail-outlined />
      </template>
     Контакты
    </a-menu-item>
  </a-menu>
</template>

<script>
export default {
  name: "TitleMenu"
}
</script>

<style scoped>

</style>
