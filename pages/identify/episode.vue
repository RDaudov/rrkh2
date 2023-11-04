<template>
   <section>
    <label for="episode">Тип эпизода</label>
    <select name="epside" id="">
        <option value="hospitalization">Госпитализация</option>
        <option value="registration">Консультация</option>
    </select>
    <label for="date">Дата эпизода</label>
    <input type="date" name="date">
    <label for="age">Возраст пациента</label>
    <input type="number" name="age">
    <label for="status">Статус эпизода</label>
    <input type="text" name="status">
   </section>
</template>