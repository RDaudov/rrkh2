<template>
    <form action="">
        <h4>Общие</h4>
        <section>
            <label for="adress">Адрес</label>
            <input type="text" name="adress">
            <label for="city">Город</label>
            <input type="text" name="city">
            <label for="index">Почтовый индекс</label>
            <input type="text" name="index">
            <label for="phone">Телефон</label>
            <input type="number" name="phone">
        </section>
        <h4>Обучение и работа</h4>
        <section>
            <label for="occupation">Тип занятости</label>
            <select type="text" name="occupation">
                <option value="worker">рабочий</option>
                <option value="pensioner">пенсионер</option>
            </select>
            <label for="work">Тип работы</label>
            <input type="text" name="work">
            <label for="occupation">Образование</label>
            <select type="text" name="occupation">
                <option value="no">нет</option>
                <option value="">среднее</option>
                <option value="">среднее специальное</option>
                <option value="">высшее</option>
            </select>
            <label for="index">Индекс</label>
            <input type="number" name="index">
        </section>
        <h4>Социально-санитарные</h4>
        <section>
            <label for="hospital">Больница</label>
            <select type="text" name="hospital">
            </select>
        </section>
        <section>
            <label for="therapist">Лечащий врач</label>
            <select type="text" name="therapist">
            </select>
        </section>
        <h4>Антропометрические данные</h4>
        <section>
            <label for="weight">Рост(кг)</label>
            <input type="number" name="weight">
            <label for="height">Вес(см)</label>
            <input type="number" name="height">
            <label for="bmi">ИМТ(кг/см2)</label>
            <input type="number" name="bmi">
            <label for="surface">Поверхность тела(м2)</label>
            <input type="number" name="surface">
        </section>
    </form>
</template>
