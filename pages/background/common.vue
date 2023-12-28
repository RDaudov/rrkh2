<template>

    <h4>Общие предшествующие данные</h4>

    <fieldset class="inputgroup">
        <div class="inputwrap">
            <label for="major-cardiac-surgery">Большая кардиохирургия</label>
            <select name="major-cardiac-surgery" id="major-cardiac-surgery">
                <option value=""></option>
            </select>
        </div>
        <div class="inputwrap">
            <label for="allergy">Аллергия</label>
            <select name="allergy" id="allergy">
                <option value=""></option>
            </select>
        </div>
        <div class="inputwrap">
            <label for="allergy-type">Тип аллергии</label>
            <input type="text" name="allergy-type" id="allergy-type" disabled>
        </div>
        <div class="inputwrap">
            <label for="obesity">Ожирение</label>
            <select name="obesity" id="obesity" disabled>
                <option value=""></option>
            </select>
        </div>
        <div class="inputwrap">
            <label for="protein-deficiency">Дефицит белка</label>
            <select name="protein-deficiency" id="protein-deficiency" disabled>
                <option value=""></option>
            </select>
        </div>
        <div class="inputwrap">
            <label for="social-support">Социальная поддержка</label>
            <select name="social-support" id="social-support">
                <option value=""></option>
            </select>
        </div>
    </fieldset>

    <h4>Дыхательная история</h4>

    <fieldset class="inputgroup">
        <div class="inputwrap">
            <label for="COPD">ХОБЛ</label>
            <select name="COPD" id="COPD">
                <option value=""></option>
            </select>
        </div>
        <div class="inputwrap">
            <label for="COPD-treatment">Лечение ХОБЛ</label>
            <select name="COPD-treatment" id="COPD-treatment" disabled>
                <option value=""></option>
            </select>
        </div>
        <div class="inputwrap">
            <label for="COPD-degree">Степень ХОБЛ</label>
            <select name="COPD-degree" id="COPD-degree">
                <option value=""></option>
            </select>
        </div>
        <div class="inputwrap">
            <label for="asthma">Астма</label>
            <select name="asthma" id="asthma">
                <option value=""></option>
            </select>
        </div>
        <div class="inputwrap">
            <label for="smoking">Курение</label>
            <select name="smoking" id="smoking">
                <option value=""></option>
            </select>
        </div>
        <div class="inputwrap">
            <label for="smoking-rate">Степень курения</label>
            <select name="smoking-rate" id="smoking-rate" disabled>
                <option value=""></option>
            </select>
        </div>
        <div class="inputwrap">
            <label for="soas">СОАС</label>
            <select name="soas" id="soas">
                <option value=""></option>
            </select>
        </div>
        <div class="inputwrap">
            <label for="pulmonary-thromboembolism">Легочная тромбоэмболия</label>
            <select name="pulmonary-thromboembolism" id="pulmonary-thromboembolism">
                <option value=""></option>
            </select>
        </div>
        <div class="inputwrap">
            <label for="other-respiratory">Другое респираторное</label>
            <select name="other-respiratory" id="other-respiratory"></select>
        </div>
    </fieldset>
</template>