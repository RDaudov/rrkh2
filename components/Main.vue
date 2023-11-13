<template>
    <Sidebar v-if="isSidebarVisible" class="sidebar"/>
    <div class="main-inner">
        <Navbar @click="showSidebar"/>
        <slot/>
    </div>
</template>
<script>
export default {
    data() {
        return {
            isSidebarVisible: false
        }
    },
    methods: {
        async showSidebar(event) {
            if(event.target.classList.contains('burger')) {
                this.isSidebarVisible = !this.isSidebarVisible
            }
        }
    }
}
</script>

st