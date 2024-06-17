<template>
    <fieldset class="inputgroup">
        <div class="inputwrap">
            <label class="required-input" for="n_qx_previous">№ Предыдущие вмешательства</label>
            <input type="number" class="form-control" id="n_qx_previous" name="n_qx_previous" min="" max="" value=""
                step="" title="" readonly="true" disabled="true">
        </div>
    </fieldset>

    <fieldset class="inputgroup">
        <div class="inputwrap">
            <label class="required-input" for="procedure_date">Дата Процедуры</label>
            <input type="date" class="form-control" id="procedure_date" name="procedure_date" min="" max="" value=""
                step="" title="">
        </div>
    </fieldset>

    <fieldset class="checkbox-group">

        <legend class="required-input">Тип Предыдущая процедура</legend>

        <div class="checkbox-wrap">
            <input id="procedure_type_coronary" class="form-check-input  " type="checkbox"
                name="procedure_type_coronary" value="1">
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
            <input id="procedure_type_vascular" class="form-check-input  " type="checkbox"
                name="procedure_type_vascular" value="1">
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
            <input id="procedure_detail_other_surgery_acquired_coronary_pathology" class="form-check-input  "
                type="checkbox" name="procedure_detail_other_surgery_acquired_coronary_pathology" value="1">
            <label class="form-check-label ">Другая операция или процедура, связанная с приобретенной</label>
        </div>

    </fieldset>

    <fieldset class="checkbox-group">

        <legend class="required-input">Подробности предыдущей процедуры — клапан</legend>

        <div class="checkbox-wrap">
            <input id="procedure_detail_mechanical_svao" class="form-check-input  " type="checkbox"
                name="procedure_detail_mechanical_svao" value="1">
            <label class="form-check-label ">Механический аортальный СВ</label>
        </div>

        <div class="checkbox-wrap">
            <input id="procedure_detail_biological_svao" class="form-check-input  " type="checkbox"
                name="procedure_detail_biological_svao" value="1">
            <label class="form-check-label ">Биологический Аортальный СВ</label>
        </div>

        <div class="checkbox-wrap">
            <input id="procedure_detail_tavi" class="form-check-input  " type="checkbox" name="procedure_detail_tavi"
                value="1">
            <label class="form-check-label ">Транскатетерный аортальный протез</label>
        </div>

        <div class="checkbox-wrap">
            <input id="procedure_detail_aortic_valve_repair" class="form-check-input  " type="checkbox"
                name="procedure_detail_aortic_valve_repair" value="1">
            <label class="form-check-label ">Ремонт аортального клапана</label>
        </div>

        <div class="checkbox-wrap">
            <input id="procedure_detail_mechanical_svmi" class="form-check-input  " type="checkbox"
                name="procedure_detail_mechanical_svmi" value="1">
            <label class="form-check-label ">СВ Митраль Механика</label>

        </div>

        <div class="checkbox-wrap"><input id="procedure_detail_biological_svmi" class="form-check-input  "
                type="checkbox" name="procedure_detail_biological_svmi" value="1"><label class="form-check-label ">SV
                Mitral
                Biológica</label>
        </div>

        <div class="checkbox-wrap">
            <input id="procedure_detail_mitral_valve_repair" class="form-check-input  " type="checkbox"
                name="procedure_detail_mitral_valve_repair" value="1">
            <label class="form-check-label ">Ремонт митрального клапана</label>
        </div>

        <div class="checkbox-wrap">
            <input id="procedure_detail_transcatheter_mitral_prosthesis" class="form-check-input  " type="checkbox"
                name="procedure_detail_transcatheter_mitral_prosthesis" value="1">
            <label class="form-check-label ">Транскатетерный митральный протез</label>
        </div>

        <div class="checkbox-wrap">
            <input id="procedure_detail_mitraplastia" class="form-check-input  " type="checkbox"
                name="procedure_detail_mitraplastia" value="1">
            <label class="form-check-label ">Чрескожная митральная пластика</label>
        </div>

        <div class="checkbox-wrap">
            <input id="procedure_detail_mitraclip" class="form-check-input  " type="checkbox"
                name="procedure_detail_mitraclip" value="1">
            <label class="form-check-label ">Чрескожный митральный зажим</label>
        </div>

        <div class="checkbox-wrap">
            <input id="procedure_detail_mitral_repair_cec_neochords" class="form-check-input  " type="checkbox"
                name="procedure_detail_mitral_repair_cec_neochords" value="1">
            <label class="form-check-label ">Восстановление митрального клапана без искусственного
                кровообращения с помощью Neochords</label>
        </div>

        <div class="checkbox-wrap">
            <input id="procedure_detail_mitral_repair_ring_cec" class="form-check-input  " type="checkbox"
                name="procedure_detail_mitral_repair_ring_cec" value="1">
            <label class="form-check-label ">Восстановление митрального кольца без искусственного кровообращения</label>
        </div>

        <div class="checkbox-wrap">
            <input id="procedure_detail_svtri_mechanical" class="form-check-input  " type="checkbox"
                name="procedure_detail_svtri_mechanical" value="1">
            <label class="form-check-label ">SV Трехстворчатый механический</label>
        </div>

        <div class="checkbox-wrap">
            <input id="procedure_detail_svtri_biological" class="form-check-input  " type="checkbox"
                name="procedure_detail_svtri_biological" value="1">
            <label class="form-check-label ">Биологический трикуспидальный СВ</label>
        </div>

        <div class="checkbox-wrap"><input id="procedure_detail_valvular_tricuspide_repair" class="form-check-input  "
                type="checkbox" name="procedure_detail_valvular_tricuspide_repair" value="1">
            <label class="form-check-label ">Ремонт трехстворчатого клапана</label>
        </div>

        <div class="checkbox-wrap">
            <input id="procedure_detail_triscuspide_transcatheter_prosthesis" class="form-check-input  " type="checkbox"
                name="procedure_detail_triscuspide_transcatheter_prosthesis" value="1">
            <label class="form-check-label ">Транскатетерный трехстворчатый протез</label>
        </div>

        <div class="checkbox-wrap">
            <input id="procedure_detail_mitraclip_triscuspide" class="form-check-input  " type="checkbox"
                name="procedure_detail_mitraclip_triscuspide" value="1">
            <label class="form-check-label ">Чрескожный трикуспидальный зажим</label>
        </div>

        <div class="checkbox-wrap">
            <input id="procedure_detail_tricuspid_repair_without_cec" class="form-check-input  " type="checkbox"
                name="procedure_detail_tricuspid_repair_without_cec" value="1">
            <label class="form-check-label ">Восстановление трикуспидального клапана с кольцом без искусственного
                кровообращения</label>
        </div>

        <div class="checkbox-wrap">
            <input id="procedure_detail_mechanical_pulmonary_prosthesis" class="form-check-input  " type="checkbox"
                name="procedure_detail_mechanical_pulmonary_prosthesis" value="1">
            <label class="form-check-label ">SV Легочный Механический</label>
        </div>

        <div class="checkbox-wrap">
            <input id="procedure_detail_biological_pulmonary_prosthesis" class="form-check-input  " type="checkbox"
                name="procedure_detail_biological_pulmonary_prosthesis" value="1">
            <label class="form-check-label ">Биологическая легочная VS</label>
        </div>

        <div class="checkbox-wrap">
            <input id="procedure_detail_pulmonary_repair" class="form-check-input  " type="checkbox"
                name="procedure_detail_pulmonary_repair" value="1">
            <label class="form-check-label ">Легочное восстановление</label>
        </div>

        <div class="checkbox-wrap">
            <input id="procedure_detail_transcatheter_pulmonary_prosthesis" class="form-check-input  " type="checkbox"
                name="procedure_detail_transcatheter_pulmonary_prosthesis" value="1">
            <label>Транскатетерный легочный SV</label>
        </div>

    </fieldset>

    <fieldset class="checkbox-group">

        <legend class="required-input">Детали предыдущей процедуры — аорта</legend>

        <div class="checkbox-wrap">
            <input id="procedure_detail_supracoronary_tubi" class="form-check-input  " type="checkbox"
                name="procedure_detail_supracoronary_tubi" value="1">
            <label class="form-check-label ">Супракоронарная трубка</label>
        </div>

        <div class="checkbox-wrap">
            <input id="procedure_detail_bentall" class="form-check-input  " type="checkbox"
                name="procedure_detail_bentall" value="1">
            <label class="form-check-label ">Бенталл</label>
        </div>

        <div class="checkbox-wrap">
            <input id="procedure_detail_preservation_substitution_aorta" class="form-check-input  " type="checkbox"
                name="procedure_detail_preservation_substitution_aorta" value="1">
            <label class="form-check-label ">Сохранение корня и замена восходящей аорты</label>
        </div>

        <div class="checkbox-wrap">
            <input id="procedure_detail_substitution_cayado" class="form-check-input  " type="checkbox"
                name="procedure_detail_substitution_cayado" value="1">
            <label class="form-check-label ">Полная или частичная замена персонала</label>
        </div>

        <div class="checkbox-wrap">
            <input id="procedure_detail_substitution_aorta_thoracic" class="form-check-input  " type="checkbox"
                name="procedure_detail_substitution_aorta_thoracic" value="1">
            <label class="form-check-label ">Полная или частичная замена нисходящей грудной аорты</label>
        </div>

        <div class="checkbox-wrap">
            <input id="procedure_detail_fet_et" class="form-check-input  " type="checkbox"
                name="procedure_detail_fet_et" value="1">
            <label class="form-check-label ">ГОТОВО/ПОКА</label>
        </div>

        <div class="checkbox-wrap">
            <input id="procedure_detail_substitution_aorta_abdominal" class="form-check-input  " type="checkbox"
                name="procedure_detail_substitution_aorta_abdominal" value="1">
            <label class="form-check-label ">Операция по замене или шунтированию брюшной аорты</label>
        </div>

        <div class="checkbox-wrap">
            <input id="procedure_detail_evar" class="form-check-input  " type="checkbox" name="procedure_detail_evar"
                value="1">
            <label class="form-check-label ">ЭВАР</label>
        </div>

        <div class="checkbox-wrap">
            <input id="procedure_detail_tevar" class="form-check-input  " type="checkbox" name="procedure_detail_tevar"
                value="1">
            <label class="form-check-label ">ТЕВААР</label>
        </div>

    </fieldset>

    <fieldset class="checkbox-group">

        <legend class="required-input">Подробности предыдущей процедуры — аритмии</legend>

        <div class="checkbox-wrap">
            <input id="procedure_detail_pacemaker_implant" class="form-check-input  " type="checkbox"
                name="procedure_detail_pacemaker_implant" value="1">
            <label class="form-check-label ">Имплантация кардиостимулятора</label>
        </div>

        <div class="checkbox-wrap">
            <input id="procedure_detail_implant_dai" class="form-check-input  " type="checkbox"
                name="procedure_detail_implant_dai" value="1">
            <label class="form-check-label ">Имплантат DAI +/-
                Resincro</label>
        </div>

        <div class="checkbox-wrap">
            <input id="procedure_detail_arrhythmia_ablation_sv" class="form-check-input  " type="checkbox"
                name="procedure_detail_arrhythmia_ablation_sv" value="1">
            <label class="form-check-label ">Абляция суправентрикулярной аритмии</label>
        </div>

        <div class="checkbox-wrap">
            <input id="procedure_detail_arrhythmia_ablation_v" class="form-check-input  " type="checkbox"
                name="procedure_detail_arrhythmia_ablation_v" value="1">
            <label class="form-check-label ">Абляция желудочковой аритмии</label>
        </div>

        <div class="checkbox-wrap"><input id="procedure_detail_surgery_fa" class="form-check-input  " type="checkbox"
                name="procedure_detail_surgery_fa" value="1">
            <label class="form-check-label ">Хирургия ФП</label>
        </div>

        <div class="checkbox-wrap"><input id="procedure_detail_surgery_arrhythmia_v" class="form-check-input  "
                type="checkbox" name="procedure_detail_surgery_arrhythmia_v" value="1">
            <label class="form-check-label ">Хирургия желудочковой аритмии</label>
        </div>

        <div class="checkbox-wrap">
            <input id="procedure_detail_endovascular_exclusion_oi" class="form-check-input  " type="checkbox"
                name="procedure_detail_endovascular_exclusion_oi" value="1">
            <label class="form-check-label ">Эндоваскулярное выключение левого придатка</label>
        </div>
        
        <div class="checkbox-wrap">
            <input id="procedure_detail_epicardial_exclusion_oi" class="form-check-input  " type="checkbox"
                name="procedure_detail_epicardial_exclusion_oi" value="1">
            <label class="form-check-label ">Эпикардиальное исключение левого придатка</label>
        </div>
        
        <div class="checkbox-wrap"><input id="procedure_detail_exclusion_os" class="form-check-input  " type="checkbox"
                name="procedure_detail_exclusion_os" value="1"><label class="form-check-label ">Исключение придатка с
                помощью шва</label>
        </div>

    </fieldset>

    <fieldset class="checkbox-group">

        <legend class="required-input">Подробности предыдущей процедуры – врожденная</legend>

        <div class="checkbox-wrap">
            <input id="procedure_detail_congenital_no" class="form-check-input  " type="checkbox"
                name="procedure_detail_congenital_no" value="1">
            <label class="form-check-label ">Без подробностей
                предыдущей процедуры</label>
        </div>

    </fieldset>

    <fieldset class="checkbox-group">

        <legend class="required-input">Деталь предыдущей процедуры – сосудистая</legend>

        <div class="checkbox-wrap">
            <input id="procedure_detail_aortoiliac_axis_derivative_surgery" class="form-check-input  " type="checkbox"
                name="procedure_detail_aortoiliac_axis_derivative_surgery" value="1">
            <label class="form-check-label ">Производная аорто-подвздошная хирургия</label>
        </div>

        <div class="checkbox-wrap">
            <input id="procedure_detail_endovascular_treatment_aortoilic_axis" class="form-check-input  "
                type="checkbox" name="procedure_detail_endovascular_treatment_aortoilic_axis" value="1">
            <label class="form-check-label ">Эндоваскулярное лечение аорто-подвздошной оси</label>
        </div>

        <div class="checkbox-wrap">
            <input id="procedure_detail_right_liofemoral_axis_surgery" class="form-check-input  " type="checkbox"
                name="procedure_detail_right_liofemoral_axis_surgery" value="1">
            <label class="form-check-label ">Производная или восстановительная операция правой подвздошно-бедренной
                оси</label>
        </div>

        <div class="checkbox-wrap">
            <input id="procedure_detail_endovascular_right_liofemoral" class="form-check-input  " type="checkbox"
                name="procedure_detail_endovascular_right_liofemoral" value="1">
            <label class="form-check-label ">Эндоваскулярное лечение правой подвздошно-бедренной оси</label>
        </div>

        <div class="checkbox-wrap">
            <input id="procedure_detail_left_liofemoral_axis_surgery" class="form-check-input  " type="checkbox"
                name="procedure_detail_left_liofemoral_axis_surgery" value="1">
            <label class="form-check-label ">Производная или восстановительная хирургия левой подвздошно-бедренной
                оси</label>
        </div>

        <div class="checkbox-wrap">
            <input id="procedure_detail_left_liofemoral_treatment" class="form-check-input  " type="checkbox"
                name="procedure_detail_left_liofemoral_treatment" value="1">
            <label class="form-check-label ">Эндоваскулярное лечение левой подвздошно-бедренной оси</label>
        </div>

        <div class="checkbox-wrap">
            <input id="procedure_detail_right_femoropopliteol_shaft_surgery" class="form-check-input  " type="checkbox"
                name="procedure_detail_right_femoropopliteol_shaft_surgery" value="1">
            <label class="form-check-label ">Производная или реконструктивная хирургия правой
                бедренно-подколенной оси</label>
        </div>
        
        <div class="checkbox-wrap">
            <input id="procedure_detail_right_femorpopliteol_treatment" class="form-check-input  " type="checkbox"
                name="procedure_detail_right_femorpopliteol_treatment" value="1">
            <label class="form-check-label ">Эндоваскулярное лечение правой бедренно-политической оси</label>
        </div>

        <div class="checkbox-wrap">
            <input id="procedure_detail_left_femoropopliteo_axis_surgery" class="form-check-input  " type="checkbox"
                name="procedure_detail_left_femoropopliteo_axis_surgery" value="1">
            <label class="form-check-label ">Производная или восстановительная хирургия левой бедренно-подколенной
                кости</label>
        </div>

        <div class="checkbox-wrap">
            <input id="procedure_detail_left_femorpopliteo_axis_treatment" class="form-check-input  " type="checkbox"
                name="procedure_detail_left_femorpopliteo_axis_treatment" value="1">
            <label class="form-check-label ">Эндоваскулярное лечение левой бедренно-подколенной
                оси</label>
        </div>

        <div class="checkbox-wrap">
            <input id="procedure_detail_right_carotideo_axis_surgery" class="form-check-input  " type="checkbox"
                name="procedure_detail_right_carotideo_axis_surgery" value="1">
            <label class="form-check-label ">Производная или реконструктивная хирургия правой сонной оси</label>
        </div>

        <div class="checkbox-wrap">
            <input id="procedure_detail_right_carotideo_treatment" class="form-check-input  " type="checkbox"
                name="procedure_detail_right_carotideo_treatment" value="1">
            <label class="form-check-label ">Эндоваскулярное лечение правой сонной артерии</label>
        </div>

        <div class="checkbox-wrap">
            <input id="procedure_detail_left_carotideo_axis_surgery" class="form-check-input  " type="checkbox"
                name="procedure_detail_left_carotideo_axis_surgery" value="1">
            <label class="form-check-label ">Производная или реконструктивная хирургия левой сонной артерии</label>
        </div>

        <div class="checkbox-wrap">
            <input id="procedure_detail_left_carotideo_treatment" class="form-check-input  " type="checkbox"
                name="procedure_detail_left_carotideo_treatment" value="1">
            <label class="form-check-label ">Эндоваскулярное лечение левой сонной артерии</label>
        </div>

    </fieldset>

</template>