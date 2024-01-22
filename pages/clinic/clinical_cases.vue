<template>
    <h4>Предоперационный критический статус</h4>
    <fieldset class="inputgroup">

        <div class="inputwrap">
            <label class="required-input" for="tv_fv_pre">Внезапная восстановительная смерть или
                предоперационная желудочковая тахикардия/фибрилляция</label>
            <select class="form-control" id="tv_fv_pre" name="tv_fv_pre" title="">
                <option value="0">Нет</option>
                <option value="1">Ага</option>
            </select>
        </div>

        <div class="inputwrap">
            <label class="required-input" for="rcp_pre">Предоперационная сердечно-легочная реанимация</label>
            <select class="form-control" id="rcp_pre" name="rcp_pre" title="">
                <option value="0">Нет</option>
                <option value="1">Ага</option>
            </select>
        </div>

        <div class="inputwrap">
            <label class="required-input" for="vmi_pre">Предоперационная механическая вентиляция легких</label>
            <select class="form-control" id="vmi_pre" name="vmi_pre" title="">
                <option value="0">Нет</option>
                <option value="1"> Ага</option>
            </select>
        </div>

        <div class="inputwrap">
            <label class="required-input" for="support_pre">Нужна поддержка</label>
            <a id="infosupport_pre" class="popInfo" href="#"
                data-content="Necesidad de Soporte Inotrópico, BCIAo o Asistencia Mecánica Circulatoria de Corto Plazo en el Momento de la Intervención"
                rel="popover" data-placement="auto" data-html="true" data-original-title="" title=""><span
                    style="color: orange;"><i class="fas fa-info-circle"></i></span>
            </a>
            <select class="form-control" id="support_pre" name="support_pre"
                title="Потребность в инотропной поддержке, ВАБК или кратковременной кровообращенной механической помощи во время вмешательства">
                <option value="0">Нет</option>
                <option value="1">Ага</option>
            </select>
        </div>

        <div class="inputwrap">
            <label class="required-input" for="oligoanuria_pre">Анурия или олигурия</label>
            <a id="infooligoanuria_pre" class="popInfo" href="#"
                data-content="Anuria, Oliguria <10ml/h, Fracaso Renal Agudo que Precise Diálisis o Filtración  en el momento de la Intervención"
                rel="popover" data-placement="auto" data-html="true" data-original-title="" title=""><span
                    style="color: orange;"><i class="fas fa-info-circle"></i></span>
            </a>
            <select class="form-control" id="oligoanuria_pre" name="oligoanuria_pre"
                title="Анурия, олигурия <10 мл/ч, острая почечная недостаточность, требующая диализа или фильтрации на момент вмешательства.">
                <option value="0">Нет</option>
                <option value="1">Ага</option>
            </select>
        </div>

        <div class="inputwrap readonly">
            <label class="required-input" for="pre_critical_state">Предоперационный критический статус</label>
            <input type="text" class="form-control" id="pre_critical_state" name="pre_critical_state" title=""
                readonly="true">
        </div>
    </fieldset>

    <h4>Другие особые клинические ситуации</h4>
    <fieldset class="inputgroup">
        <div class="inputwrap">
            <label class="required-input" for="preoperative_fra">Предыдущая почечная недостаточность</label> 
            <a id="infopreoperative_fra" class="popInfo" href="#"
                data-content="<ul><li>Fracaso Renal Agudo.</li><li>Estadio I de AKIN: Aumento de Creatinina sérica más de 0.3 mg/dL o 1,5-2 veces el valor basal, o reducción de la diuresis <0,5 l/kg/h más de 6 horas.</li><li>Estadio II de AKIN: Aumento de la Cr  2-3 veces el valor basal o reducción de la diuresis <0.5 ml/kg/h 12 horas o más.</li><li>Estadio III de AKIN: Aumento de Cr 3 o más veces, o creatinina >4 mg/dL o terapia renal sustititutiva o diuresis <0.5 ml/Kg/h 24 horas o más o anuria de más de 12 horas.</li></ul>"
                rel="popover" data-placement="auto" data-html="true" data-original-title="" title=""><span
                    style="color: orange;"><i class="fas fa-info-circle"></i></span>
            </a>
            <select class="form-control"
                id="preoperative_fra" name="preoperative_fra"
                title="<ul><li>Острая почечная недостаточность.</li><li>АКИН Стадия I: Увеличение сывороточного креатинина более чем на 0,3 мг/дл или в 1,5-2 раза по сравнению с исходным значением или снижение диуреза < 0,5 л/кг/ч более 6 часов.</li><li>АКИН Стадия II: Увеличение Cr в 2-3 раза по сравнению с исходным значением или снижение диуреза <0,5 мл/кг/ч в течение 12 часов и более. </li><li>AKIN Стадия III: Увеличение Cr в 3 или более раз, или креатинин >4 мг/дл, или заместительная почечная терапия, или диурез <0,5 мл/кг/ч в течение 24 часов или более, или анурия более 12 часов.</li></ul>">
                <option value="0">Нет</option>
                <option value="1">Этап I</option>
                <option value="2">II этап</option>
                <option value="3">III этап</option>
            </select>
        </div>

        <div class="inputwrap">
            <label class="required-input" for="shockcardio_pre">Предоперационный кардиогенный шок</label> 
            <select class="form-control" id="shockcardio_pre" name="shockcardio_pre" title="">
                <option value="0">Нет</option>
                <option value="1">Ага</option>
            </select>
        </div>

        <div class="inputwrap">
            <label class="required-input" for="icc_pre">Предоперационная застойная сердечная недостаточность</label> 
            <select class="form-control" id="icc_pre" name="icc_pre" title="">
                <option value="0">Нет</option>
                <option value="1">Ага</option>
            </select>
        </div>

        <div class="inputwrap">
            <label for="compli_pci_pre">Осложнение ангиопластики или эндоваскулярного лечения</label> 
            <select class="form-control" id="compli_pci_pre" name="compli_pci_pre" title="">
                <option value="0">Нет</option>
                <option value="1">Ага</option>
            </select>
        </div>
        <div class="inputwrap">
            <label for="thrombolysis_pre">Посттромболизисное состояние</label> 
            <select class="form-control" id="thrombolysis_pre" name="thrombolysis_pre" title="">
                <option value="0">Нет</option>
                <option value="1">Ага</option>
            </select>
        </div>
        <div class="inputwrap">
            <label for="preoperative_coma">Предоперационная кома</label> 
            <select class="form-control" id="preoperative_coma" name="preoperative_coma" title="">
                <option value="0">Нет</option>
                <option value="1">Ага</option>
            </select>
        </div>
        <div class="inputwrap">
            <label for="iam_pre_evolution">Развитие IAM</label> 
            <select class="form-control" id="iam_pre_evolution" name="iam_pre_evolution" title="">
                <option value="0">Нет</option>
                <option value="1">Ага</option>
            </select>
        </div>
    </fieldset>
</template>