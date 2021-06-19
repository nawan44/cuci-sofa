<template>
    <div id="portofolio">
        <h1>OUR WORK</h1>
        <hr class="line-section"/>
        <hr class="line-section"/>
        <h5>Examples of our work which represent our marketing capabilities.</h5>
        <div class="row-swiper">
            <SwiperPorto/>

        </div>
    </div>
</template>
<style scoped="scoped">
     @import '../assets/style/App.css';
    @import '../assets/style/portofolio.css'; 
</style>


<script>
    import SwiperPorto from './SwiperPorto.vue'

    export default {name: 'Portofolio', components: {
            SwiperPorto
        }}
</script>