<template>
    <form class="form" action="" method="post" >
        <label for="name">Имя</label>
        <input type="text" name="firtname">
        <label for="lastname">Фамилия</label>
        <input type="text" name="lastname">
        <label for="surname">Отчество</label>
        <input type="text" name="surname">
        <label for="history">Номер истории</label>
        <input type="number" name="history">
        <div class="documents">
            <input type="checkbox" name="passport">
            <label for="passport">Паспорт</label>
            <input type="checkbox" name="snils">
            <label for="snils">Снилс</label>
        </div>
        <label for="passport">Паспорт</label>
        <input type="text" name="passport">
        <label for="snils">Снилс</label>
        <input type="text" name="snils">
        <label for="date">Дата рождения</label>
        <input type="date" name="date"/>
        <label for="sex"></label>
        <select name="sex">
            <option value="male">Мужской</option>
            <option value="female" selected>Женский</option>
        </select>
        <label for="race">Раса</label>
        <select name="race">
            <option value="caucasoid" selected>Кавказоидная</option>
            <option value="mongolian">Монголоидная</option>
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