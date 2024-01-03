<template>
    <div class="tabs">
        <NuxtLink class="tab-link" to="/identify/control">Основные</NuxtLink>
        <NuxtLink class="tab-link" to="/identify/registration">Регистрация</NuxtLink>
        <NuxtLink class="tab-link" to="/identify/episode">Эпизод</NuxtLink>
    </div>
    <slot/> 
</template>
<style scoped>
.tabs {
    display: flex;
    justify-content: flex-start;
    border-bottom: 1px solid #acb1b4;
    margin-bottom: 20px;
}

.link {
    padding: 5px 10px;
    margin-bottom: -1px;
}

.router-link-active {
    border:1px solid #acb1b4;
    border-bottom: 2px solid white;
}
</style>