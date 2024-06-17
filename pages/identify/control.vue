<template>
    <form class="form" action="" method="post">
        <div class="inputgroup">
            <div class="inputwrap">
                <label class="required-input" for="name">Имя</label>
                <input type="text" name="firtname" id="name" autocomplete="on">
            </div>
            <div class="inputwrap">
                <label class="required-input" for="lastname">Фамилия</label>
                <input type="text" name="lastname" id="lastname">
            </div>
            <div class="inputwrap">
                <label for="surname">Отчество</label>
                <input type="text" name="surname" id="surname">
            </div>
            <div class="inputwrap">
                <label class="required-input" for="history">Номер истории</label>
                <input type="number" name="history" id="history">
            </div>
        </div>
        <div class="documents">
            <div class="checkbox-wrapper">
                <input type="checkbox" name="passport" id="passport-ok">
                <label for="passport">Паспорт</label>
            </div>
            <div class="checkbox-wrapper">
                <input type="checkbox" name="snils" id="snils-ok">
                <label for="snils">Снилс</label>
            </div>
        </div>
        <div class="inputgroup">
            <div class="inputwrap">
                <label for="passport">Паспорт</label>
                <input type="text" name="passport" id="passport">
            </div>
            <div class="inputwrap">
                <label for="snils">Снилс</label>
                <input type="text" name="snils" id="snils">
            </div>
        </div>
            <div class="inputgroup">
                <div class="inputwrap">
                <label class="required-input" for="date">Дата рождения</label>
                <input type="date" name="date" id="date"/>
            </div>
            <div class="inputwrap"><label for="sex"></label>
                <label class="required-input" for="sex">Пол</label>
                <select name="sex" id="sex">
                    <option value="male">Мужской</option>
                    <option value="female" selected>Женский</option>
                </select>
            </div>
            <div class="inputwrap">
                <label class="required-input" for="race">Раса</label>
                <select name="race" id="race">
                    <option value="caucasoid" selected>Кавказоидная</option>
                    <option value="mongolian">Афроамерианец</option>
                    <option value="asian">Азиат</option>
                </select>
            </div>
        </div>
    </form>
</template>
<style lang="scss" scoped>
.documents {
    display: flex;
    flex-wrap: wrap;
    margin: 0 5px 20px;
    padding: 2px 5px;
    width: 98%;
    .checkbox-wrapper {
        display: flex;
        align-items: center;
        width: 25%;
    }
}
</style>