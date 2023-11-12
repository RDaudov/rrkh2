
import { Burger } from '#build/components';
<template>
  <nav class="navbar">
    <Sidebar v-if="isActive"/>
    <Burger @click="isActive = !isActive" class="{ active: isActive} burger" />
    <ul class="nav-left">
        <li class="item">
            <b>ПАЦИЕНТ:</b>
            <span>Хосе  Кабалеро</span>
        </li>
        <li class="item">
            <b>ЭПИЗОД:</b>
            <span>госпитализация</span>
        </li>
        <li class="item">
            <b>ДАТА:</b>
            <span>06/05/2023</span>
        </li>
    </ul>
    <div class="nav-right">
        <button>1</button>
        <button>2</button>
    </div>
</nav>
</template>

<script>
export default {
    data() {
    return {
      isActive: false
    }
}

}
</script>

<style>
.navbar {
    display: flex;
    justify-content: flex-start;
    align-items: center;
}

.nav-right {
    display: flex;
    flex-direction: column;
    margin-left: auto;
}
</style>