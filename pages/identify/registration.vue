<template>
    <form>

        <h4>Общие</h4>

        <section class="inputgroup">
            <div class="inputwrap">
                <label for="adress">Адрес</label>
                <input type="text" name="adress" id="adress">
            </div>
            <div class="inputwrap">
                <label for="city">Город</label>
                <input type="text" name="city" id="city">
            </div>
            <div class="inputwrap">
                <label for="index">Почтовый индекс</label>
                <input type="text" name="index" id="post-index">
            </div>
            <div class="inputwrap">
                <label for="phone">Телефон</label>
                <input type="number" name="phone" id="phone" autocomplete="on">
            </div>
        </section>

        <h4>Обучение и работа</h4>

        <section class="inputgroup">
            <div class="inputwrap">
                <label for="occupation">Тип занятости</label>
                <select type="text" name="occupation" id="occupation">
                    <option value="worker">рабочий</option>
                    <option value="pensioner">пенсионер</option>
                </select>
            </div>
            <div class="inputwrap">
                <label for="work">Тип работы</label>
                <input type="text" name="work" id="work">
            </div>
            <div class="inputwrap">
                <label for="education">Образование</label>
                <select type="text" name="education" id="education">
                    <option value="no">нет</option>
                    <option value="">среднее</option>
                    <option value="">среднее специальное</option>
                    <option value="">высшее</option>
                </select>
            </div>
            <div class="inputwrap">
                <label for="index">Индекс</label>
                <input type="number" name="index" id="index">
            </div>
        </section>

        <h4>Социально-санитарные</h4>

        <section class="inputgroup">
            <div class="inputwrap">
                <label for="hospital">Больница</label>
                <select type="text" name="hospital" id="hospital">
                </select>
            </div>
            <div class="inputwrap">
                <label for="therapist">Лечащий врач</label>
                <select type="text" name="therapist" id="therapist">
                </select>
            </div>
        </section>

        <h4>Антропометрические данные</h4>

        <section class="inputgroup">
            <div class="inputwrap">
                <label class="required-input" for="weight">Рост(кг)</label>
                <input type="number" name="weight" id="weight">
            </div>
            <div class="inputwrap">
                <label class="required-input" for="height">Вес(см)</label>
                <input type="number" name="height" id="height">
            </div>
            <div class="inputwrap">
                <label class="required-input" for="bmi">ИМТ(кг/см2)</label>
                <input type="number" name="bmi" id="bmi">
            </div>
            <div class="inputwrap">
                <label class="required-input" for="surface">Поверхность тела(м2)</label>
                <input type="number" name="surface" id="surface">
            </div>
        </section>
    </form>
</template>
