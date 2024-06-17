<template>
    <main class="main" @click="hideSidebar">
        <div class="sidebar-wrapper" id="sidebar">
            <Sidebar/>
        </div>
        <div class="main-inner">
            <Navbar @click="showSidebar">
                <Burger :class="{active: isSidebarVisible}"/>
            </Navbar>
            <slot/>
        </div>
    </main>
</template>
<script>
export default {
    data() {
        return {
            isSidebarVisible: false
        }
    },
    methods: {
        showSidebar(event) {
            if(event.target.classList.contains('burger')) {
                this.isSidebarVisible = !this.isSidebarVisible
                document.querySelector('#sidebar').classList.toggle('active')
            }
        },
    }
}
</script>
 <style lang="scss" scoped>

 .main {
    display: flex;
    overflow: hidden;
    position: relative;
    min-width: 100vw;
 }

 .sidebar-wrapper {
    height: calc(100dvh - 80px);
    display: flex;
    background-color: rgba($color: #000000, $alpha: 0);
    margin-left: -15rem;
    transition: 
    margin .5s, 
    background-color 1s;
    &.active{
            margin-left: 0;
            background-color: rgba($color: #000000, $alpha: .3);
        }
 }

 .main-inner {
    width: 100%;
    min-width: 100vw;
    height: calc(100dvh - 80px);
    overflow: scroll;
 }

 @media(min-width: 768px) {
    .sidebar-wrapper {
        margin-left: 0;
        &.active {
            margin-left: -15rem;
        }
    }

    .main-inner {
    overflow: scroll;
    min-width: 0;
 }
}
 </style>