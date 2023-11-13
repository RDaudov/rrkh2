<template>
    <form>
        <h4>Общие</h4>
        <section>
            <label for="adress">Адрес</label>
            <input type="text" name="adress" id="adress">
            <label for="city">Город</label>
            <input type="text" name="city" id="city">
            <label for="index">Почтовый индекс</label>
            <input type="text" name="index" id="post-index">
            <label for="phone">Телефон</label>
            <input type="number" name="phone" id="phone" autocomplete="on">
        </section>
        <h4>Обучение и работа</h4>
        <section>
            <label for="occupation">Тип занятости</label>
            <select type="text" name="occupation" id="occupation">
                <option value="worker">рабочий</option>
                <option value="pensioner">пенсионер</option>
            </select>
            <label for="work">Тип работы</label>
            <input type="text" name="work" id="work">
            <label for="education">Образование</label>
            <select type="text" name="education" id="education">
                <option value="no">нет</option>
                <option value="">среднее</option>
                <option value="">среднее специальное</option>
                <option value="">высшее</option>
            </select>
            <label for="index">Индекс</label>
            <input type="number" name="index" id="index">
        </section>
        <h4>Социально-санитарные</h4>
        <section>
            <label for="hospital">Больница</label>
            <select type="text" name="hospital" id="hospital">
            </select>
        </section>
        <section>
            <label for="therapist">Лечащий врач</label>
            <select type="text" name="therapist" id="therapist">
            </select>
        </section>
        <h4>Антропометрические данные</h4>
        <section>
            <label for="weight">Рост(кг)</label>
            <input type="number" name="weight" id="weight">
            <label for="height">Вес(см)</label>
            <input type="number" name="height" id="height">
            <label for="bmi">ИМТ(кг/см2)</label>
            <input type="number" name="bmi" id="bmi">
            <label for="surface">Поверхность тела(м2)</label>
            <input type="number" name="surface" id="surface">
        </section>
    </form>
</template>
