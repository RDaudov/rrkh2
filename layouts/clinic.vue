<template>
    <div class="tabs">
        <NuxtLink class="tab-link" to="/clinic/control">Общие</NuxtLink>
        <NuxtLink class="tab-link" to="/clinic/clinical_syndrome">Клинический синдром</NuxtLink>
        <NuxtLink class="tab-link" to="/clinic/clinical_cases">Клинические ситуации</NuxtLink>
        <NuxtLink class="tab-link" to="/clinic/vascular_syndromes">Сосудистые синдромы</NuxtLink>
    </div>
    <slot/>
</template>
