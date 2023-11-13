<template>
    <form class="form" action="" method="post">
        <label for="name">Имя</label>
        <input type="text" name="firtname" id="name" autocomplete="on">
        <label for="lastname">Фамилия</label>
        <input type="text" name="lastname" id="lastname">
        <label for="surname">Отчество</label>
        <input type="text" name="surname" id="surname">
        <label for="history">Номер истории</label>
        <input type="number" name="history" id="history">
        <div class="documents">
            <input type="checkbox" name="passport" id="passport-ok">
            <label for="passport">Паспорт</label>
            <input type="checkbox" name="snils" id="snils-ok">
            <label for="snils">Снилс</label>
        </div>
        <label for="passport">Паспорт</label>
        <input type="text" name="passport" id="passport">
        <label for="snils">Снилс</label>
        <input type="text" name="snils" id="snils">
        <label for="date">Дата рождения</label>
        <input type="date" name="date" id="date"/>
        <label for="sex"></label>
        <select name="sex" id="sex">
            <option value="male">Мужской</option>
            <option value="female" selected>Женский</option>
        </select>
        <label for="race">Раса</label>
        <select name="race" id="race">
            <option value="caucasoid" selected>Кавказоидная</option>
            <option value="mongolian">Афроамерианец</option>
            <option value="asian">Азиат</option>
        </select>
    </form>
</template>
<style scoped>
.documents {
    border: 1px solid grey;
    margin: 2px;
    padding: 2px 5px;
}
</style>