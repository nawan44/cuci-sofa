<template>
     <div class="header">
             <Navmenu/>

        <div>
            <div>
                <img src="../assets/logo/logo.png" class="logo-header"></div>
                <div>
                    <h1 class="brand-name">Rachwan</h1>
                </div>
                <div>
                    <hr class="line-header"/></div>
                <div><hr class="line-header"/></div>
                <div>
                    <h2 class="tag-line">Reach Your Global</h2>
                </div>
                <div>
                    <div class="arrow">
                        <a class="btn-arrow" href="#about">
                            <i class='far fa-arrow-alt-circle-down font-arrow'></i>
                        </a>
                    </div>
                </div>
            </div>
        </div>
</template>

<style scoped="scoped">
     @import '../assets/style/header.css';
</style>
    <script>
        import Navmenu from './Navmenu.vue'

        export default {name: 'Header', components: {
                Navmenu
            }}
    </script>