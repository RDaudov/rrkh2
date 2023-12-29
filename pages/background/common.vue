<template>
    <h4>Общие предшествующие данные</h4>

    <fieldset class="inputgroup">
        <div class="inputwrap">
            <label class="required-input" for="previous_major_surgery">Большая кардиохирургия</label>
            <select class="form-control" id="previous_major_surgery" name="previous_major_surgery" title="">
                <option value="0">Нет</option>
                <option value="1">Да</option>
            </select>
        </div>
        <div class="inputwrap">
            <label for="previous_allergies">Аллергия</label>
            <select class="form-control" id="previous_allergies" name="previous_allergies" title="">
                <option value="1000"></option>
                <option value="0">Нет </option>
                <option value="1">Да</option>
            </select>
        </div>
        <div class="inputwrap">
            <label for="allergy-type">Тип аллергии</label>
            <input type="text" name="allergy-type" id="allergy-type" disabled>
        </div>
        <div class="inputwrap">
            <label for="obesity">Ожирение</label>
            <select class="form-control" id="obesity" name="obesity" title="" readonly="">
                <option value="0">Нет</option>
            </select>
        </div>
        <div class="inputwrap">
            <label for="malnutrition">Недоедание</label>
            <select class="form-control" id="malnutrition" name="malnutrition" title="" readonly="">
                <option value="0">Нет</option>
            </select>
        </div>
        <div class="inputwrap">
            <label for="social-support">Социальная поддержка</label>
            <select class="form-control" id="social_support" name="social_support" title="">
                <option value="1000"></option>
                <option value="0">Нет</option>
                <option value="1">Да</option>
            </select>
        </div>
    </fieldset>

    <h4>Дыхательная история</h4>

    <fieldset class="inputgroup">
        <div class="inputwrap">
            <label class="required-input" for="epoc">ХОБЛ</label>
            <select class="form-control" id="epoc" name="epoc" title="">
                <option value="1000"></option>
                <option value="0">Нет</option>
                <option value="1">И</option>
            </select>
        </div>
        <div class="inputwrap">
            <label class="required-input" for="epoc-treatment">Лечение ХОБЛ</label>
            <select class="form-control" id="epoc_treatment" name="epoc_treatment" title="" disabled="true">
                <option value="0">Что-либо</option>
                <option value="1">Бронхолитики</option>
                <option value="2">Кислородная терапия</option>
            </select>
        </div>
        <div class="inputwrap">
            <label class="required-input" for="epoc_grade">Степень ХОБЛ</label>
            <select class="form-control" id="epoc_grade" name="epoc_grade" title="" disabled="true">
                <option value="0">Не ХОБЛ</option>
                <option value="1">Уровень (Золотой 1) ОФВ1 &gt;= 80%</option>
                <option value="2">Умеренный (Золотой 2) ОФВ1 50-79%</option>
                <option value="3">Северо (Золото 3) ОФВ1 30-49%</option>
                <option value="4">Очень тяжелый (Золотой 4) ОФВ1 &lt; 30%</option>
            </select>
        </div>
        <div class="inputwrap">
            <label for="asthma">Астма</label>
            <select class="form-control" id="asthma" name="asthma" title="">
                <option value="1000"></option>
                <option value="0">Нет</option>
                <option value="1">Да</option>
            </select>
        </div>
        <div class="inputwrap">
            <label for="smoking">Курение</label>
            <select class="form-control" id="smoking" name="smoking" title="">
                <option value="1000"></option>
                <option value="0">Нет</option>
                <option value="1">Да, уволился больше месяца назад</option>
                <option value="2">Да, нынешний курильщик</option>
            </select>
        </div>
        <div class="inputwrap">
            <label for="smoking-rate">Степень курения</label>
            <input type="number" class="form-control" id="smoking_level" name="smoking_level" min="" max="" value="" step=""
                title="Текущий уровень потребления (упаковка/год)" disabled="true">
        </div>
        <div class="inputwrap">
            <label for="obstructive_sleep_apnea">СОАС</label>
            <select class="form-control" id="obstructive_sleep_apnea" name="obstructive_sleep_apnea" title="">
                <option value="1000"></option>
                <option value="0">Нет</option>
                <option value="1">Да</option>
            </select>
        </div>
        <div class="inputwrap">
            <label for="pulmonary-embolism">Легочная тромбоэмболия</label>
            <select class="form-control" id="pulmonary_embolism" name="pulmonary_embolism" title="">
                <option value="1000"></option>
                <option value="0">Нет</option>
                <option value="1">Да</option>
            </select>
        </div>
        <div class="inputwrap">
            <label for="other-respiratory">Другое респираторное</label>
            <select class="form-control" id="other_respiratory" name="other_respiratory" title="">
                <option value="1000"></option>
                <option value="0">Нет</option>
                <option value="1">Да</option>
            </select>
        </div>
    </fieldset>

    <h4>Метаболическая эндокринная история</h4>

    <fieldset class="inputgroup">
        <div class="inputwrap">
            <label class="required-input" for=" diabetes ">Диабет</label>
            <select class=" form-control " id=" diabetes " name=" diabetes " title="">
                <option value=" 1000 "></option>
                <option value=" 0 ">Нет</option>
                <option value=" 1 ">Лечится диетой</option>
                <option value=" 2 ">Лечится пероральными противодиабетическими средствами</option>
                <option value=" 3 ">Лечение инсулином</option>
            </select>
        </div>
        <div class="inputwrap">
            <label class="required-input" for="evp">Периферические артериальные заболевания</label>
            <select class=" form-control " id="evp" name=" diabetes " title="">
                <option value=" 1000 "></option>
                <option value=" 0 ">Нет</option>
                <option value=" 1 ">Да</option>
            </select>
        </div>
        <div class="inputwrap">
            <label for="arterial_hypertension">Артериальная гипертензия</label>
            <select class=" form-control " id="arterial_hypertension" name=" diabetes " title="">
                <option value=" 1000 "></option>
                <option value=" 0 ">Нет</option>
                <option value=" 1 ">Да, без медицинского лечения</option>
                <option value=" 2 ">Да, лечился медикаментозно</option>
            </select>
        </div>
        <div class="inputwrap">
            <label for="hypertriglyceridemia">Гипертриглицеридемия</label>
            <select class=" form-control " id="hypertriglyceridemia" name=" diabetes " title="">
                <option value=" 1000 "></option>
                <option value=" 0 ">Нет</option>
                <option value=" 1 ">Да, без медицинского лечения</option>
                <option value=" 2 ">Да, лечился медикаментозно</option>
            </select>
        </div>
        <div class="inputwrap">
            <label for="hypercholesterolemia">Гиперхолестеринемия</label>
            <select class=" form-control " id="hypercholesterolemia" name=" diabetes " title="">
                <option value=" 1000 "></option>
                <option value=" 0 ">Нет</option>
                <option value=" 1 ">Да, без медицинского лечения</option>
                <option value=" 2 ">Да, лечился медикаментозно</option>
            </select>
        </div>
        <div class="inputwrap">
            <label for="thyroid">Щитовидная железа</label>
            <select class=" form-control " id="thyroid" name=" diabetes " title="">
                <option value=" 1000 "></option>
                <option value=" 0 ">Нет</option>
                <option value=" 1 ">Невылеченный гипотериоз</option>
                <option value=" 2 ">Вылеченный гипотериоз</option>
            </select>
        </div>
        <div class="inputwrap">
            <label for="ulcus">Желудочно-кишечная язва</label>
            <select class="form-control" id="ulcus" name="ulcus" title="">
                <option value="0">Нет</option>
                <option value="1">Да, без медицинского лечения</option>
                <option value="2">а, лечился медикаментозно</option>
                <option value="1000"></option>
            </select>
        </div>
        <div class="inputwrap">
            <label for="alcoholism">Алкоголизм</label>
            <select class="form-control" id="alcoholism" name="alcoholism" title="">
                <option value="0">Нет</option>
                <option value="1">Да, без медицинского лечения </option>
                <option value="2">Да, лечился медикаментозно </option>
                <option value="1000"></option>
            </select>
        </div>
        <div class="inputwrap">
            <label for="hyperuricemia">Гиперурикемия</label>
            <select class="form-control" id="hyperuricemia" name="hyperuricemia" title="">
                <option value="0">Нет</option>
                <option value="1">Да, не лечится медикаментозно</option>
                <option value="2">Да, медикаментозное лечение</option>
                <option value="1000"></option>
            </select>
        </div>
        <div class="inputwrap">
            <label for="connective_heart_disease">Заболевания соединительной ткани</label>
            <select class="form-control" id="connective_heart_disease" name="connective_heart_disease" title="">
                <option value="0">Нет</option>
                <option value="1">Сд Марфан</option>
                <option value="2">лер Данлос</option>
                <option value="3">Лойс-Дитц</option>
                <option value="4">Акта 2</option>
                <option value="5">Семейная аневризма грудной клетки</option>
                <option value="6">Другие</option>
                <option value="1000"></option>
            </select>
        </div>
        <div class="inputwrap">
            <label for="family_history_ischemic_heart_disease">Семейный анамнез ишемической болезни сердца</label>
            <select class="form-control" id="family_history_ischemic_heart_disease"
                name="family_history_ischemic_heart_disease" title="">
                <option value="0">Нет</option>
                <option value="1">Да</option>
            </select>
        </div>
    </fieldset>

    <h4>Неврологическая история</h4>

    <fieldset class="inputgroup">
        <div class="inputwrap">
            <label class="mandatory" for="acv_preview">Предыдущий инсульт</label>
            <select class="form-control" id="acv_preview" name="acv_preview" title="">
                <option value="0">Нет</option>
                <option value="1">И</option>
            </select>
        </div>
        <div class="inputwrap">
            <label for="ait_preview">Предыдущий АИТ</label>
            <select class="form-control" id="ait_preview" name="ait_preview"
                title="Предшественник транзиторной ишемической атаки или беглого амавроза">
                <option value="1000"></option>
                <option value="0">Нет </option>
                <option value="1">Да</option>
            </select>
        </div>
        <div class="inputwrap">
            <label for="mental_retardation">Интеллектуальная недееспособность</label> <select class="form-control"
                id="mental_retardation" name="mental_retardation" title="">
                <option value="1000"></option>
                <option value="0">Нет</option>
                <option value="1">Да</option>
            </select>
        </div>
        <div class="inputwrap">
            <label for="epilepsy">Эпилепсия</label>
            <select class="form-control" id="epilepsy" name="epilepsy" title="">
                <option value="1000"></option>
                <option value="0">Нет</option>
                <option value="1">Да</option>
            </select>
        </div>
    </fieldset>

    <h4>Почечная история</h4>

    <fieldset class="checkbox-group">
        <legend>Хроническая болезнь почек</legend>

        <div class="checkbox-wrap">
            <input id="chronic_kidney_disease_no" class="form-check-input" type="checkbox" name="chronic_kidney_disease_no"
                value="1">
            <label class="form-check-label">Нет</label>
        </div>

        <div class="checkbox-wrap">
            <input id="chronic_Kidney_disease_Stage_3" class="form-check-input backChroKidDis " type="checkbox"
                name="chronic_Kidney_disease_Stage_3" value="1" disabled="true">
            <label class="form-check-label ">KIDGO Хроническая болезнь почек 3 стадии (СКФ&lt;60)</label>
        </div>

        <div class="checkbox-wrap">
            <input id="chronic_Kidney_disease_Stage_4" class="form-check-input backChroKidDis " type="checkbox"
                name="chronic_Kidney_disease_Stage_4" value="1" disabled="true">
            <label class="form-check-label ">Хроническая болезнь почек 4 стадии KIDGO (СКФ&lt;30)</label>
        </div>

        <div class="checkbox-wrap">
            <input id="chronic_Kidney_disease_Stage_5" class="form-check-input backChroKidDis " type="checkbox"
                name="chronic_Kidney_disease_Stage_5" value="1" disabled="true">
            <label class="form-check-label ">Хроническая болезнь почек 5 стадии KIDGO (TFG&lt;15)</label>
        </div>

        <div class="checkbox-wrap">
            <input id="chronic_Kidney_disease_albuminuria30" class="form-check-input backChroKidDis " type="checkbox"
                name="chronic_Kidney_disease_albuminuria30" value="1" disabled="true">
            <label class="form-check-label ">Альбуминурия 30-300 мг/г</label>
        </div>

        <div class="checkbox-wrap">
            <input id="chronic_Kidney_disease_albuminuria300" class="form-check-input backChroKidDis " type="checkbox"
                name="chronic_Kidney_disease_albuminuria300" value="1" disabled="true">
            <label class="form-check-label ">Альбуминурия &gt;300 мг/г</label>
        </div>

        <div class="checkbox-wrap">
            <input id="chronic_Kidney_disease_dialysis" class="form-check-input backChroKidDis " type="checkbox"
                name="chronic_Kidney_disease_dialysis" value="1" disabled="true">
            <label class="form-check-label ">Диализ</label>
        </div>

        <div class="checkbox-wrap">
            <input id="chronic_Kidney_disease_kidney_transplant" class="form-check-input backChroKidDis " type="checkbox"
                name="chronic_Kidney_disease_kidney_transplant" value="1" disabled="true">
            <label class="form-check-label ">Пересадка почки</label>
        </div>
    </fieldset>

    <h4>Инфекционная история</h4>

    <fieldset class="inputgroup">

        <div class="inputwrap">
            <label for="vih">ВИЧ</label>
            <select class="form-control" id="vih" name="vih" title="">
                <option value="0">Нет</option>
                <option value="1">Ага</option>
                <option value="1000"></option>
            </select>
        </div>

        <div class="inputwrap">
            <label for="hepatitis_b">Гепатит Б</label>
            <select class="form-control" id="hepatitis_b" name="hepatitis_b" title="">
                <option value="0">Нет</option>
                <option value="1">Ага</option>
                <option value="1000"></option>
            </select>
        </div>

        <div class="inputwrap">
            <label for="hepatitis_c">Гепатит С</label>
            <select class="form-control" id="hepatitis_c" name="hepatitis_c" title="">
                <option value="0">Нет</option>
                <option value="1">Ага</option>
                <option value="1000"></option>
            </select>
        </div>

        <div class="inputwrap">
            <label for="advp">АДВП</label>
            <select class="form-control" id="advp" name="advp" title="">
                <option value="0">Нет</option>
                <option value="1">Ага</option>
                <option value="2"></option>
            </select>
        </div>

        <div class="inputwrap">
            <label for="hepatic_cirrhosis">Цирроз печени</label>
            <select class="form-control" id="hepatic_cirrhosis" name="hepatic_cirrhosis" title="">
                <option value="0">Нет</option>
                <option value="1">РЕБЕНОК А</option>
                <option value="2">РЕБЕНОК Б</option>
                <option value="3">РЕБЕНОК С</option>
                <option value="1000"></option>
            </select>
        </div>
    </fieldset>

    <h4>Онкологический гематологический анамнез</h4>

    <fieldset class="inputgroup">

        <div class="inputwrap">
            <label for="neoplasms">Новообразования</label> 
            <select class="form-control" id="neoplasms" name="neoplasms" title="">
                <option value="0">Нет</option>
                <option value="1"> Ага</option>
                <option value="1000"></option>
            </select>
        </div>

        <div class="inputwrap">
            <label for="solid_tumor">Солидная опухоль</label> 
            <select class="form-control" id="solid_tumor" name="solid_tumor" title="">
                <option value="0">Нет</option>
                <option value="1">Ага</option>
                <option value="1000"></option>
            </select>
        </div>

        <div class="inputwrap">
            <label for="heparin_induced_thrombopenia">Гепарин-индуцированная тромбопения</label> 
            <select class="form-control" id="heparin_induced_thrombopenia" name="heparin_induced_thrombopenia"
                title="">
                <option value="0">Нет</option>
                <option value="1">Ага</option>
                <option value="1000"></option>
            </select>
        </div>

        <div class="inputwrap"><label for="lymphoma_leukemia">Лейкемия/Линфома</label> 
            <select class="form-control" id="lymphoma_leukemia" name="lymphoma_leukemia" title="">
                <option value="0">Нет</option>
                <option value="1">Ага</option>
                <option value="1000"></option>
            </select>
        </div>

        <div class="inputwrap">
            <label for="coagulopathy">Коагулопатия</label> 
            <select class="form-control" id="coagulopathy" name="coagulopathy" title="">
                <option value="0">Нет</option>
                <option value="1">Ага</option>
                <option value="1000"></option>
            </select>
        </div>
    </fieldset>

</template>