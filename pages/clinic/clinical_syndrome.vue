<template>
    <fieldset class="checkbox-group">

        <legend>Клиника</legend>

        <div class="checkbox-wrap">
            <input id="asymptomatic_clinical_syndrome" class="form-check-input  " type="checkbox"
                name="asymptomatic_clinical_syndrome" value="1">
            <label class="form-check-label ">Бессимптомный</label>
        </div>

        <div class="checkbox-wrap"><input id="dyspnoea_clinical_syndrome" class="form-check-input clinic_chk "
                type="checkbox" name="dyspnoea_clinical_syndrome" value="1">
            <label class="form-check-label ">Одышка</label>
        </div>

        <div class="checkbox-wrap">
            <input id="silent_myocardial_ischemia_clinical_syndrome" class="form-check-input clinic_chk " type="checkbox"
                name="silent_myocardial_ischemia_clinical_syndrome" value="1">
            <label class="form-check-label ">Тихая ишемия миокарда</label>
        </div>

        <div class="checkbox-wrap">
            <input id="presyncope_clinical_syndrome" class="form-check-input clinic_chk " type="checkbox"
                name="presyncope_clinical_syndrome" value="1">
            <label class="form-check-label ">Пресинкопе</label>
        </div>

        <div class="checkbox-wrap">
            <input id="syncope_clinical_syndrome" class="form-check-input clinic_chk " type="checkbox"
                name="syncope_clinical_syndrome" value="1">
            <label class="form-check-label ">обморок</label>
        </div>

        <div class="checkbox-wrap">
            <input id="angina_clinical_syndrome" class="form-check-input clinic_chk " type="checkbox"
                name="angina_clinical_syndrome" value="1">
            <label class="form-check-label ">Стенокардия</label>
        </div>

        <div class="checkbox-wrap">
            <input id="thoracic_pain_clinical_syndrome" class="form-check-input clinic_chk " type="checkbox"
                name="thoracic_pain_clinical_syndrome" value="1">
            <label class="form-check-label ">Боль в груди, кроме стенокардии</label>
        </div>

        <div class="checkbox-wrap">
            <input id="ait_clinical_syndrome" class="form-check-input clinic_chk " type="checkbox"
                name="ait_clinical_syndrome" value="1">
            <label class="form-check-label ">АИТ</label>
        </div>

        <div class="checkbox-wrap">
            <input id="ictus_clinical_syndrome" class="form-check-input clinic_chk " type="checkbox"
                name="ictus_clinical_syndrome" value="1">
            <label class="form-check-label ">Гладить</label>
        </div>

        <div class="checkbox-wrap">
            <input id="clinical_syndrome_limb_ischemia" class="form-check-input clinic_chk " type="checkbox"
                name="clinical_syndrome_limb_ischemia" value="1">
            <label class="form-check-label ">Ишемия конечностей</label>
        </div>

        <div class="checkbox-wrap">
            <input id="arrhythmia_clinical_syndrome" class="form-check-input clinic_chk " type="checkbox"
                name="arrhythmia_clinical_syndrome" value="1">
            <label class="form-check-label ">Аритмии</label>
        </div>

        <div class="checkbox-wrap">
            <input id="cyanosis_clinical_syndrome" class="form-check-input clinic_chk " type="checkbox"
                name="cyanosis_clinical_syndrome" value="1">
            <label class="form-check-label ">Цианоз</label>
        </div>
    </fieldset>

    <fieldset class="inputgroup">

        <div class="inputwrap">
            <label class="required-input" for="nyha">NYHA</label>
            <select class="form-control" id="nyha" name="nyha" title="">
                <option value="1">я</option>
                <option value="2">II</option>
                <option value="3">III</option>
                <option value="4">IV</option>
            </select>
        </div>

        <div class="inputwrap">
            <label class="required-input" for="ccs_angor">CCS</label>
            <a id="infoccs_angor" class="popInfo" href="#" data-content="Clase funcional para angina según la CCS"
                rel="popover" data-placement="auto" data-html="true" data-original-title="" title="">
                <span style="color: orange;"><i class="fas fa-info-circle"></i></span></a>
            <select class="form-control" id="ccs_angor" name="ccs_angor" title="Функциональный класс стенокардии по СКС">
                <option value="0">0</option>
                <option value="1">1</option>
                <option value="2">2</option>
                <option value="3">3</option>
                <option value="4">4</option>
            </select>
        </div>

        <div class="inputwrap">
            <label for="test_6_m">тест на 6 метров</label>
            <a id="infotest_6_m" class="popInfo" href="#"
                data-content="Test de la Marcha de los 6 Metros. Variable cuantitativa (enteros de 0 a 100 segundos)"
                rel="popover" data-placement="auto" data-html="true" data-original-title="" title="">
                <span style="color: orange;"><i class="fas fa-info-circle"></i></span></a>
            <input type="number" class="form-control" id="test_6_m" name="test_6_m" min="" max="" value="" step=""
                title="Тест ходьбы на 6 метров. Количественная переменная (целые числа от 0 до 100 секунд)">
        </div>

        <div class="inputwrap">
            <label for="intermacs">ИНТЕРМАКС</label>
            <a id="infointermacs" class="popInfo" href="#"
                data-content="Es una escala categórica ordinal con niveles del 1 al 7" rel="popover" data-placement="auto"
                data-html="true" data-original-title="" title=""><span style="color: orange;"><i
                        class="fas fa-info-circle"></i></span></a>
            <input type="number" class="form-control" id="intermacs" name="intermacs" min="0" max="7" value="" step=""
                title="Это порядковая категориальная шкала с уровнями от 1 до 7.">
        </div>

        <div class="inputwrap">
            <label class="required-input" for="active_endocarditis">Активный эндокардит</label>
            <select class="form-control" id="active_endocarditis" name="active_endocarditis" title="">
                <option value="1000"></option>
                <option value="0">Нет</option>
                <option value="1">Ага</option>
            </select>
        </div>
    </fieldset>

    <h4>Острые коронарные синдромы</h4>
    <fieldset class="inputgroup">
        <div class="inputwrap   ">
            <label for="coronary_syndrome">Тип последнего коронарного синдрома</label>
            <select class="form-control" id="coronary_syndrome" name="coronary_syndrome" title="">
                <option value="0">Нет</option>
                <option value="1">Стабильная стенокардия</option>
                <option value="2"> СКАСЕСТ</option>
                <option value="3">СКАСЕСТ</option>
            </select>
        </div>

        <div class="inputwrap coronary_syndrome_scasest">
            <label for="braunwald_classification">Классификация Браунвальда</label>
            <a id="infobraunwald_classification" class="popInfo" href="#"
                data-content="Clasificación Braunwald último Episodio de Angina Inestable" rel="popover"
                data-placement="auto" data-html="true" data-original-title="" title=""><span style="color: orange;">
                    <i class="fas fa-info-circle"></i></span>
            </a>
            <select class="form-control" id="braunwald_classification" name="braunwald_classification"
                title="Классификация Браунвальда Последний эпизод нестабильной стенокардии">
                <option value="1">Я</option>
                <option value="2">ИМА</option>
                <option value="3">IIА</option>
                <option value="4">ИБ</option>
                <option value="5">МИБ</option>
                <option value="6">IIIБ</option>
                <option value="7">IC</option>
                <option value="8">ИИК</option>
                <option value="9">IIIC</option>
            </select>
        </div>

        <div class="inputwrap coronary_syndrome_scasest">
            <label for="scasest_time">Предыдущее время SCASEST</label>
            <a id="infoscasest_time" class="popInfo" href="#" data-content="Tiempo desde último SCASEST Previo"
                rel="popover" data-placement="auto" data-html="true" data-original-title="" title=""><span
                    style="color: orange;"><i class="fas fa-info-circle"></i></span>
            </a>
            <select class="form-control" id="scasest_time" name="scasest_time"
                title="Время с момента последнего ACS Предыдущее">
                <option value="1">Равно или больше 90 дней</option>
                <option value="2">От 7 дней до 90 дней</option>
                <option value="3">Менее 7 дней</option>
                <option value="4">Менее 72 часов</option>
                <option value="5">Менее 25 часов</option>
                <option value="6">Часы</option>
            </select>
        </div>

        <div class="inputwrap   ">
            <label for="iam_previous">Предыдущий инфаркт</label>
            <select class="form-control" id="iam_previous" name="iam_previous" title="">
                <option value="0">Нет</option>
                <option value="1">Ага</option>
            </select>
        </div>
    </fieldset>

    <h4>Неврологическая клиника</h4>
    <fieldset class="inputgroup">

        <div class="inputwrap">
            <label class="mandatory" for="reduced_mobility">Сниженная подвижность</label> 
            <select class="form-control" id="reduced_mobility" name="reduced_mobility" title="">
                <option value="1000"></option>
                <option value="0">Нет</option>
                <option value="1">Ага</option>
            </select>
        </div>

        <div class="inputwrap">
            <label class="mandatory" for="neurological_dysfunction">Неврологическая дисфункция</label> 
            <a id="infoneurological_dysfunction" class="popInfo" href="#"
                data-content="Daño Neurológico que Afecte Severamente a la Deambulación o a la Actividad Cotidiana"
                rel="popover" data-placement="auto" data-html="true" data-original-title="" title=""><span
                    style="color: orange;"><i class="fas fa-info-circle"></i></span>
            </a>
            <select class="form-control"
                id="neurological_dysfunction" name="neurological_dysfunction"
                title="Неврологические повреждения, серьезно влияющие на ходьбу или повседневную активность">
                <option value="1000"></option>
                <option value="0">Нет</option>
                <option value="1">Ага</option>
            </select>
        </div>

        <div class="inputwrap">
            <label for="getup_chair">Вставая со стула</label> 
            <select class="form-control" id="getup_chair" name="getup_chair" title="">
                <option value="1000"></option>
                <option value="1">Встаньте со стула 5 раз за &lt; 15 сек.</option>
                <option value="2">Встаньте со стула 5 раз в &gt; 15 сек.</option>
                <option value="3">Не завершен</option>
            </select>
        </div>

    </fieldset>
</template>