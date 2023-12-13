
import { Header } from '#build/components';
<template>
  <header class="header">
    <NuxtLink to="/" class="logo">LOGO</NuxtLink>
    <div class="burger-wrap">
      <Burger @click="isMenuVisible = !isMenuVisible" :class="{active: isMenuVisible}"/>
    </div>
    <main-menu class="main-menu" v-if="isMenuVisible"/>
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
    border: 2px solid #acb1b4;
    background-color: #f8f9fa;
    padding: 0 20px;
    flex-wrap: wrap;
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
  flex: 1 0 100%;
}
</style>