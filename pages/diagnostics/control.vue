<template>
    <div class="textarea-wrap">
        <label for="diagnostics">Диагностика</label>
        <textarea class="form-control" id="diagnostics" name="diagnostics" title="" rows="3"></textarea>
    </div>
    <fieldset class="inputgroup">
        <div class="inputwrap">
            <label class="mandatory" for="indicacion">Indicación</label>
            <select class="form-control" id="indicacion" name="indicacion" title="">
                <option value="0">Intervención Quirúrgica</option>
                <option value="1">Revisión en Consultas</option>
                <option value="2">Inclusión en Lista de Espera</option>
            </select>
        </div>
        <div class="inputwrap">
            <label for="indicacion_prioridad">Prioridad de la Indicación</label>
            <a id="infoindicacion_prioridad" class="popInfo" href="#"
                data-content="Criterios de ordenación temporal de las intervenciones quirúrgicas en patología cardiovascular y endovascular adquirida. Versión 2022. DOI: 10.1016/j.circv.2022.06.009"
                rel="popover" data-placement="auto" data-html="true" data-original-title="" title=""><span
                    style="color: orange;"><i class="fas fa-info-circle"></i></span></a>
            <select class="form-control" id="indicacion_prioridad" name="indicacion_prioridad"
                title="Criterios de ordenación temporal de las intervenciones quirúrgicas en patología cardiovascular y endovascular adquirida. Versión 2022. DOI: 10.1016/j.circv.2022.06.009">
                <option value="1000"></option>
                <option value="0">0</option>
                <option value="1">1</option>
                <option value="2">2a</option>
                <option value="3">2b</option>
                <option value="4">3</option>
                <option value="5">4</option>
                <option value="6">5</option>
            </select>
        </div>
    </fieldset>
    <div class="textarea-wrap">
            <label for="backMedicationDose">Хирургическое показание</label>
            <textarea class="form-control" id="backMedicationDose" name="backMedicationDose" title="" rows="3"></textarea>
    </div>
</template>