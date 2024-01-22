<template>
    <div class="sidebar">
      <ul class="menu">
        <li class="link"><NuxtLink to="/identify">Данные</NuxtLink></li>
        <li class="link"><NuxtLink to="/background">Предшествующие данные</NuxtLink></li>
        <li class="link"><NuxtLink to="/previous">Ранние вмешательства</NuxtLink></li>
        <li class="link"><NuxtLink href="/clinic">Клиника</NuxtLink></li>
        <li class="link"><NuxtLink href="/exploration">Исследования</NuxtLink></li>
        <li class="link"><NuxtLink href="/diagnostics">Диагнозы</NuxtLink></li>
        <li class="link"><NuxtLink href="7">Операция</NuxtLink></li>
        <li class="link"><a href="8">Перфузия / Анестезия</a></li>
        <li class="link"><a href="9">UVI / UCQ</a></li>
        <li class="link"><a href="10">Выписка</a></li>
      </ul>
      <div class="buttons">
        <button class="btn btn-red">События</button>
        <button class="btn">Отчеты</button>
      </div>
    </div>
</template>

<style lang="scss" scoped>
.sidebar {
  border: 2px solid #acb1b4;
  background-color: #F6F9FB;
  width: 60%;
}

.menu {
  margin: 0 0 20px;
}

.link {
  display: flex;
  align-items: center;
  height: 40px;
  color: #6B6B6B;
  border-top: 2px solid #acb1b4;
  &:first-child {
    border-top: none;
  }
  &:last-child {
    border-bottom: 2px solid #acb1b4;
  }
  
}

.router-link-active {
  display: flex;
  align-items: center;
  width: 100%;
  height: 40px;
  color: #6B6B6B;
  background-color: #cacdcf;
  font-weight: bold;
}

.buttons {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.btn {
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: transparent;
  height: 40px;
  width: 150px;
  padding: 0 40px;
  margin-bottom: 15px;
  border-radius: 5px;
  border-width: 1px;
}

.btn-red {
  color: rgb(230, 30, 30);
  border: 1px solid rgb(230, 30, 30);
}

</style>