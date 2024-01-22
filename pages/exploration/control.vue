<template>
    <fieldset class="inputgroup">
        <div class="inputwrap">
            <label for="exploration_date">Дата исследования</label>
            <input type="date" class="form-control" id="exploration_date" name="exploration_date">
        </div>
    </fieldset>
    
    <fieldset class="checkbox-group">

        <div class="checkbox-wrap">
            <input id="tipo_exploracion_basica" class="form-check-input  " type="checkbox" name="tipo_exploracion_basica" value="1" checked>
            <label class="form-check-label ">Базовое исследование</label>
        </div>

        <div class="checkbox-wrap">
            <input id="tipo_exploracion_analitica" class="form-check-input  " type="checkbox" name="tipo_exploracion_analitica" value="1" checked>
            <label class="form-check-label ">Аналитика/Микробиология</label>
        </div>

        <div class="checkbox-wrap">
            <input id="tipo_exploracion_radiologia" class="form-check-input  " type="checkbox" name="tipo_exploracion_radiologia" value="1" checked>
            <label class="form-check-label ">Простая радиология грудной клетки</label>
        </div>

        <div class="checkbox-wrap">
            <input id="tipo_exploracion_eggholter" class="form-check-input  " type="checkbox" name="tipo_exploracion_eggholter" value="1" checked>
            <label class="form-check-label ">ЭКГ или Холтер</label>
        </div>

        <div class="checkbox-wrap">
            <input id="tipo_exploracion_ecocardiograma" class="form-check-input  " type="checkbox" name="tipo_exploracion_ecocardiograma" value="1" checked>
            <label class="form-check-label ">ЭКО ТТ и ТЕ</label>
        </div>

        <div class="checkbox-wrap">
            <input id="tipo_exploracion_hemodinamica" class="form-check-input  " type="checkbox" name="tipo_exploracion_hemodinamica" value="1" checked>
            <label class="form-check-label ">Гемодинамическое исследование</label>
        </div>

        <div class="checkbox-wrap">
            <input id="tipo_exploracion_tac" class="form-check-input  " type="checkbox" name="tipo_exploracion_tac" value="1" checked>
            <label class="form-check-label ">ТК / ТАК ТАВИ</label>
        </div>

        <div class="checkbox-wrap">
            <input id="tipo_exploracion_rmn" class="form-check-input  " type="checkbox" name="tipo_exploracion_rmn" value="1">
            <label class="form-check-label ">МРТ</label>
        </div>

        <div class="checkbox-wrap">
            <input id="tipo_exploracion_respiratorias" class="form-check-input  " type="checkbox" name="tipo_exploracion_respiratorias" value="1">
            <label class="form-check-label ">Респираторные функциональные тесты</label>
        </div>

        <div class="checkbox-wrap">
            <input id="tipo_exploracion_ecodoppler" class="form-check-input  " type="checkbox" name="tipo_exploracion_ecodoppler" value="1">
            <label class="form-check-label ">ЭкоДопплер Сосудистый</label>
        </div>

        <div class="checkbox-wrap">
            <input id="tipo_exploracion_espamacs" class="form-check-input  " type="checkbox" name="tipo_exploracion_espamacs" value="1">
            <label class="form-check-label ">Переменные</label>
        </div>
        
        <div class="checkbox-wrap">
            <input id="tipo_exploracion_otras" class="form-check-input  " type="checkbox" name="tipo_exploracion_otras" value="1">
            <label class="form-check-label ">Другие тесты</label>
        </div>
    </fieldset>
</template>