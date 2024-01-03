<template>
  <nav class="nav">
    <ul class="nav-item left">
        <li class="link">Меню</li>
        <li class="link">Обслуживание</li>
        <li class="link">Статистика</li>
        <li class="link">График</li>
        <li class="link">Часто задаваемые вопросы</li>
    </ul>
    <ul class="nav-item right">
        <li class="link">200</li>
        <li class="link">Пользователь</li>
        <li class="link">Выход</li>
    </ul>
  </nav>
</template>

<style lang="scss" scoped>

@media (min-width: 1240px) {
  .nav-item {
    display: flex;
    justify-content: space-between;
    gap: 10px;
  }
}
</style>
