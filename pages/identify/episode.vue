<template>
   <section class="inputgroup">
    <div class="inputwrap">
        <label for="episode">Тип эпизода</label>
        <select name="epside" id="episode">
            <option value="hospitalization">Госпитализация</option>
            <option value="registration">Консультация</option>
        </select>
    </div>
    <div class="inputwrap">
        <label for="date">Дата эпизода</label>
        <input type="date" name="date" id="date">
    </div>
    <div class="inputwrap">
        <label for="age">Возраст пациента</label>
        <input type="number" name="age" id="age">
    </div>
    <div class="inputwrap">
        <label for="status">Статус эпизода</label>
        <input type="text" name="status" id="status">
    </div>
   </section>
</template>