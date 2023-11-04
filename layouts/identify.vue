<template>
    <div class="tabs">
        <NuxtLink to="/identify/control">Основные</NuxtLink>
        <NuxtLink to="/identify/registration">Регистрация</NuxtLink>
        <NuxtLink to="/identify/episode">Эпизод</NuxtLink>
    </div>
    <slot/> 
</template>
<style scoped>
.tabs {
    display: flex;
    justify-content: flex-start;
}
a {
    color: black;
    text-decoration: none;
    padding: 0 5px;
}
</style>