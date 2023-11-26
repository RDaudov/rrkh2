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
                this.isSidebarVisible = true
                document.querySelector('#sidebar').classList.toggle('active')
                document.querySelector('.main-inner').classList.toggle('active')
            }
        },
        hideSidebar(event) {
            if(event.target.classList.contains("sidebar-wrapper")) {
                this.isSidebarVisible = false
                document.querySelector('#sidebar').classList.toggle('active')
                document.querySelector('.main-inner').classList.toggle('active')
            }
        }
    }
}
</script>
 <style lang="scss" scoped>

 .main {
    display: flex;
    overflow: hidden;
    position: relative;
 }

 .sidebar-wrapper {
    position: absolute;
  left: 0;
  top: 0;
  z-index: 99;
  width: 100%;
  height: 100vh;
  display: flex;
  background-color: rgba($color: #000000, $alpha: 0);
  transform: translateX(-100%);
  transition: 
  transform .5s, 
  background-color 1s;
    &.active{
            transform: translateX(0%);
            background-color: rgba($color: #000000, $alpha: .3);
        }
 }

 .main-inner {
    width: 100%;
    height: 100vh;
    transform: translateX(0%);
    transition: .5s;
        &.active{
            transform: translateX(60%);
        }
 }
 </style>