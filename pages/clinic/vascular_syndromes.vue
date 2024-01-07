<template>
    <h4>Каротидный шум и венозные заболевания</h4>
    <fieldset class="inputgroup">
        <div class="inputwrap">
            <label for="carotid_murmur">Каротидный шум</label>
            <select class="form-control" id="carotid_murmur" name="carotid_murmur" title="">
                <option value="0">Нет</option>
                <option value="1">Левый</option>
                <option value="2">Верно</option>
                <option value="3">двусторонний</option>
            </select>
        </div>
    </fieldset>

    <fieldset class="checkbox-group">
        <legend>Венозная болезнь</legend>
        <div class="checkbox-wrap">
            <input id="venous_disease_no" class="form-check-input  " type="checkbox" name="venous_disease_no" value="1">
            <label class="form-check-label ">Нет</label>
        </div>

        <div class="checkbox-wrap">
            <input id="venous_disease_varicose" class="form-check-input  " type="checkbox" name="venous_disease_varicose"
                value="1">
            <label class="form-check-label ">Варикозная болезнь</label>
        </div>

        <div class="checkbox-wrap">
            <input id="venous_disease_trombosis_fp" class="form-check-input  " type="checkbox"
                name="venous_disease_trombosis_fp" value="1">
            <label class="form-check-label ">Тромбоз Фем-Поп</label>
        </div>

        <div class="checkbox-wrap">
            <input id="venous_disease_dermatitis" class="form-check-input  " type="checkbox"
                name="venous_disease_dermatitis" value="1">
            <label class="form-check-label ">Дерматит</label>
        </div>

        <div class="checkbox-wrap">
            <input id="venous_disease_trombosis_ic" class="form-check-input  " type="checkbox"
                name="venous_disease_trombosis_ic" value="1">
            <label class="form-check-label ">Тромбоз</label>
        </div>

        <div class="checkbox-wrap">
            <input id="venous_disease_ulceration" class="form-check-input  " type="checkbox"
                name="venous_disease_ulceration" value="1">
            <label class="form-check-label ">Изъязвление</label>
        </div>

        <div class="checkbox-wrap">
            <input id="venous_disease_tep" class="form-check-input  " type="checkbox" name="venous_disease_tep" value="1">
            <label class="form-check-label ">Легочная тромбоэмболия</label>
        </div>

        <div class="checkbox-wrap">
            <input id="venous_disease_trombosis_sup" class="form-check-input  " type="checkbox"
                name="venous_disease_trombosis_sup" value="1">
            <label class="form-check-label ">Тромбоз поверхностный</label>
        </div>
    </fieldset>

    <h4>Хроническая ишемия</h4>
    <fieldset class="inputgroup">
        <div class="inputwrap">
            <label class="required-input" for="chronic_ischemia">Оценка хронической ишемии</label>
            <select class="form-control" id="chronic_ischemia" name="chronic_ischemia" title="">
                <option value="0">Нет</option>
                <option value="1"> Ага</option>
            </select>
        </div>
    </fieldset>

    <fieldset class="checkbox-group">
        <legend>Конечность с хронической ишемией</legend>
        <div class="checkbox-wrap">
            <input id="limb_chronic_ischemia_sd" class="form-check-input limb_chronic_ischemia " type="checkbox"
                name="limb_chronic_ischemia_sd" value="1" disabled="true">
            <label class="form-check-label ">Крайность С.Д.</label>
        </div>

        <div class="checkbox-wrap">
            <input id="limb_chronic_ischemia_si" class="form-check-input limb_chronic_ischemia " type="checkbox"
                name="limb_chronic_ischemia_si" value="1" disabled="true">
            <label class="form-check-label ">СИ Крайность</label>
        </div>

        <div class="checkbox-wrap">
            <input id="limb_chronic_ischemia_id" class="form-check-input limb_chronic_ischemia " type="checkbox"
                name="limb_chronic_ischemia_id" value="1" disabled="true">
            <label class="form-check-label ">Идентификатор конечности</label>
        </div>

        <div class="checkbox-wrap">
            <input id="limb_chronic_ischemia_ii" class="form-check-input limb_chronic_ischemia " type="checkbox"
                name="limb_chronic_ischemia_ii" value="1" disabled="true">
            <label class="form-check-label ">Крайность И.И.</label>
        </div>
    </fieldset>

    <h4>Острая ишемия</h4>
    <fieldset class="inputgroup">
        <div class="inputwrap">
            <label for="acute_ischemia">Оценка острой ишемии</label>
            <select class="form-control" id="acute_ischemia" name="acute_ischemia" title="">
                <option value="0">Нет</option>
                <option value="1">Ага</option>
            </select>
        </div>
    </fieldset>

    <fieldset class="checkbox-group">
        <legend>Пораженный сегмент конечности – острая ишемия</legend>
        <div class="checkbox-wrap">
            <input id="acute_ischemia_segment_esd" class="form-check-input acute_ischemia_segment " type="checkbox"
                name="acute_ischemia_segment_esd" value="1" disabled="true">
            <label class="form-check-label ">Крайность С.Д.</label>
        </div>

        <div class="checkbox-wrap">
            <input id="acute_ischemia_segment_esi" class="form-check-input acute_ischemia_segment " type="checkbox"
                name="acute_ischemia_segment_esi" value="1" disabled="true">
            <label class="form-check-label ">СИ Крайность</label>
        </div>

        <div class="checkbox-wrap">
            <input id="acute_ischemia_segment_eid" class="form-check-input acute_ischemia_segment " type="checkbox"
                name="acute_ischemia_segment_eid" value="1" disabled="true">
            <label class="form-check-label ">Идентификатор конечности</label>
        </div>
        
        <div class="checkbox-wrap">
            <input id="acute_ischemia_segment_eii" class="form-check-input acute_ischemia_segment " type="checkbox"
                name="acute_ischemia_segment_eii" value="1" disabled="true">
            <label class="form-check-label ">Крайность И.И.</label>
        </div>

        <div class="checkbox-wrap">
            <input id="acute_ischemia_segment_ta" class="form-check-input acute_ischemia_segment " type="checkbox"
                name="acute_ischemia_segment_ta" value="1" disabled="true">
            <label class="form-check-label ">Конечная аорта</label>
        </div>

        <div class="checkbox-wrap">
            <input id="acute_ischemia_segment_tc" class="form-check-input acute_ischemia_segment " type="checkbox"
                name="acute_ischemia_segment_tc" value="1" disabled="true">
            <label class="form-check-label ">Целиакия Хобот</label>
        </div>

        <div class="checkbox-wrap">
            <input id="acute_ischemia_segment_rd" class="form-check-input acute_ischemia_segment " type="checkbox"
                name="acute_ischemia_segment_rd" value="1" disabled="true">
            <label class="form-check-label ">Реналь Д.</label>
        </div>

        <div class="checkbox-wrap">
            <input id="acute_ischemia_segment_ri" class="form-check-input acute_ischemia_segment " type="checkbox"
                name="acute_ischemia_segment_ri" value="1" disabled="true">
            <label class="form-check-label ">Реналь И.</label>
        </div>

        <div class="checkbox-wrap">
            <input id="acute_ischemia_segment_me" class="form-check-input acute_ischemia_segment " type="checkbox"
                name="acute_ischemia_segment_me" value="1" disabled="true">
            <label class="form-check-label ">Брыжеечный</label>
        </div>
    </fieldset>
</template>