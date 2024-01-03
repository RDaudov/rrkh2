
import { Header } from '#build/components';
<template>
  <header class="header" :class="{collapsed: isMenuVisible}">
    <NuxtLink to="/" class="logo">LOGO</NuxtLink>
    <div class="burger-wrap">
      <Burger @click="isMenuVisible = !isMenuVisible" :class="{active: isMenuVisible}"/>
    </div>
    <main-menu class="main-menu" v-show="isMenuVisible"/>
  </header>
</template>

<script>
import MainMenu from './MainMenu.vue'
export default {
  components: { MainMenu },
  data() {
    return {
      isMenuVisible: false
    }
  }
}
</script>

<style scoped>
.header {
    height: 70px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
    gap: 20px;
    border: 2px solid #acb1b4;
    background-color: #f8f9fa;
    padding: 0 20px;
    position: sticky;
    top: 0;
    z-index: 1;
    margin-bottom: 10px;
}

.logo {
  color: black;
  text-decoration: none;
  font-size: 30px;
}
.burger-wrap {
  display: flex;
  justify-content: flex-start;
  align-items: center;
  padding: 5px 10px;
  border: 1px solid grey;
  border-radius: 5px;
}
.main-menu {
  flex: 1 1 100%;
  flex-basis: 100%;
  background-color: #f8f9fa;
  border: 2px solid #acb1b4;
  border-top: none;
  margin: 0 -22px;
  padding: 5px 10px;
}

@media(min-width: 1240px) {

  .header {
    flex-wrap: nowrap;
  }

  .burger-wrap {
    display: none;
  }

  .main-menu {
    display: flex !important;
    justify-content: space-between;
    margin: 8px 0 0;
    padding: 0;
    border: none;
  }
}
</style>