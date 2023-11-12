
import { Header } from '#build/components';
<template>
  <header class="header">
    <NuxtLink to="/" class="logo">LOGO</NuxtLink>
    <div class="burger-wrap">
      <Burger @click="isActive = !isActive" :class="{active: isActive}"/>
    </div>
    <main-menu class="main-menu" v-if="isActive"/>
  </header>
</template>

<script>
import MainMenu from './MainMenu.vue'
export default {
  components: { MainMenu },
  data() {
    return {
      isActive: false
    }
  }
}
</script>

<style scoped>
.header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: #f8f9fa;
    padding: 0 20px;
    flex-wrap: wrap;
    position: sticky;
    top: 0;
    z-index: 1;
}

.logo {
  color: black;
  text-decoration: none;
  font-size: 30px;
}
.burger-wrap {
  width: 40px;
  height: 40px;
  display: flex;
  justify-content: start;
  align-items: center;
  padding: 5px 10px;
  border: 1px solid grey;
  border-radius: 5px;
}
.main-menu {
  flex: 1 0 100%;
}
</style>