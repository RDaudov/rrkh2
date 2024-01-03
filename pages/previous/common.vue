<template>
    <fieldset class="inputgroup">
        <div class="inputwrap">
            <label class="required-input" for="n_qx_previous">№ Предыдущие вмешательства</label>
            <input type="number" class="form-control" id="n_qx_previous" name="n_qx_previous" min="" max="" value="" step=""
                title="" readonly="true" disabled="true">
        </div>
    </fieldset>

    <fieldset class="inputgroup">
        <div class="inputwrap">
            <label class="required-input" for="procedure_date">Дата Процедуры</label>
            <input type="date" class="form-control" id="procedure_date" name="procedure_date" min="" max="" value="" step=""
                title="">
        </div>
    </fieldset>

    <fieldset class="checkbox-group">

        <legend class="required-input">Тип Предыдущая процедура</legend>

        <div class="checkbox-wrap">
            <input id="procedure_type_coronary" class="form-check-input  " type="checkbox" name="procedure_type_coronary"
                value="1">
            <label class="form-check-label ">коронарный</label>
        </div>

        <div class="checkbox-wrap">
            <input id="procedure_type_valve" class="form-check-input  " type="checkbox" name="procedure_type_valve"
                value="1">
            <label class="form-check-label ">клапанный</label>
        </div>

        <div class="checkbox-wrap">
            <input id="procedure_type_aorta" class="form-check-input  " type="checkbox" name="procedure_type_aorta"
                value="1">
            <label class="form-check-label ">Аорта</label>
        </div>

        <div class="checkbox-wrap">
            <input id="procedure_type_arrhythmia" class="form-check-input  " type="checkbox"
                name="procedure_type_arrhythmia" value="1">
            <label class="form-check-label ">Аритмии</label>
        </div>

        <div class="checkbox-wrap">
            <input id="procedure_type_congenital" class="form-check-input  " type="checkbox"
                name="procedure_type_congenital" value="1">
            <label class="form-check-label ">Врожденный</label>
        </div>

        <div class="checkbox-wrap">
            <input id="procedure_type_vascular" class="form-check-input  " type="checkbox" name="procedure_type_vascular"
                value="1">
            <label class="form-check-label ">Сосудистый</label>
        </div>

        <div class="checkbox-wrap">
            <input id="procedure_type_transplant" class="form-check-input  " type="checkbox"
                name="procedure_type_transplant" value="1">
            <label class="form-check-label ">Трансплантация/долгосрочный уход</label>
        </div>

        <div class="checkbox-wrap">
            <input id="procedure_type_other" class="form-check-input  " type="checkbox" name="procedure_type_other"
                value="1">
            <label class="form-check-label ">Другой</label>
        </div>

    </fieldset>

    <fieldset class="checkbox-group">

        <legend class="required-input">Детали процедуры – коронарная болезнь</legend>

        <div class="checkbox-wrap">
            <input id="procedure_detail_coronary" class="form-check-input  " type="checkbox"
                name="procedure_detail_coronary" value="1">
            <label class="form-check-label ">Коронарное шунтирование</label>
        </div>

        <div class="checkbox-wrap">
            <input id="procedure_detail_icp_sin_stent" class="form-check-input  " type="checkbox"
                name="procedure_detail_icp_sin_stent" value="1">
            <label class="form-check-label ">ПМС без стента</label>
        </div>

        <div class="checkbox-wrap">
            <input id="procedure_detail_icp_con_stent" class="form-check-input  " type="checkbox"
                name="procedure_detail_icp_con_stent" value="1">
            <label class="form-check-label ">ДЦП с обычным стентом</label>
        </div>

        <div class="checkbox-wrap">
            <input id="procedure_detail_icp_constent" class="form-check-input  " type="checkbox"
                name="procedure_detail_icp_constent" value="1">
            <label class="form-check-label ">ЧКВ с закрытым стентом</label>
        </div>

        <div class="checkbox-wrap">
            <input id="procedure_detail_breaking_surgery" class="form-check-input  " type="checkbox"
                name="procedure_detail_breaking_surgery" value="1">
            <label class="form-check-label "> VI Свободная хирургия разрыва стенки</label>
        </div>

        <div class="checkbox-wrap">
            <input id="procedure_detail_civ_surgery" class="form-check-input  " type="checkbox"
                name="procedure_detail_civ_surgery" value="1">
            <label class="form-check-label ">Постинфарктная хирургия ДМПП</label>
        </div>

        <div class="checkbox-wrap">
            <input id="procedure_detail_aneurysm_surgery" class="form-check-input  " type="checkbox"
                name="procedure_detail_aneurysm_surgery" value="1">
            <label class="form-check-label "> Постинфарктная хирургия аневризмы желудочка</label>
        </div>

        <div class="checkbox-wrap">
            <input id="procedure_detail_other_surgery_acquired_coronary_pathology"
                class="form-check-input  " type="checkbox" name="procedure_detail_other_surgery_acquired_coronary_pathology"
                value="1">
            <label class="form-check-label ">Другая операция или процедура, связанная с приобретенной</label>
        </div>

</fieldset></template>