<template>
<div id="app">
  <!-- aside-menu 左側欄 -->
<AsideMenu/>

  <!-- 地圖區塊 -->
  <div class="mask-map" id="mask-map"></div>
</div>
</template>
<script>
import AsideMenu from './components/asideMenu.vue'
export default {
  name: 'App',
  components: { AsideMenu }
}
</script>

<style lang="scss" src="./assets/style.scss"></style>
