<template>
  <div class="sidebar">
    <ul class="menu">
    <li class="link"><NuxtLink to="/identify">Данные</NuxtLink></li>
    <li class="link"><NuxtLink to="/background">Предшествующие данные</NuxtLink></li>
    <li class="link"><a href="3">Ранние вмешательства</a></li>
    <li class="link"><a href="4">Клиника</a></li>
    <li class="link"><a href="5">Исследования</a></li>
    <li class="link"><a href="6">Диагнозы</a></li>
    <li class="link"><a href="7">Операция</a></li>
    <li class="link"><a href="8">Перфузия / Анестезия</a></li>
    <li class="link"><a href="9">UVI / UCQ</a></li>
    <li class="link"><a href="10">Выписка</a></li>
  </ul>
  <button>События</button>
  <button>Отчеты</button>
  </div>
</template>

<style>
.sidebar {
  display: flex;
  flex-direction: column;
}

</style>