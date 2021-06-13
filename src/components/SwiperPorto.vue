<template>

    <div class="swiper-porto">
        <swiper class="swiper" :options="swiperOption">
            <swiper-slide>
                <div class="swip-con">
                    <img src="../assets/portofolio/port1.jpg" class="img-swiper"/>
                    <div class="description-job">
                        <h2>Job :
                        </h2>
                        <h3 class="job">
                            Sponsorship, Media Partner, Events, Digital Campaign, Brand Activities, Sales
                            Leverage
                        </h3>
                        <hr class="line-section"/>
                        <h2>Brand :
                        </h2>
                        <h4 class="desc">
                            Berniaga.com, Kacang Garuda, Hotels for Roadshow, 30 Media partners, in 5
                            cities, Gala Premiere, Press Screening, Nobar, Meet and Greet, Talkshow,
                            Interview, Road Show

                        </h4>
                    </div>
                </div>

            </swiper-slide>
            <swiper-slide>
                <div class="swip-con">
                    <img src="../assets/portofolio/port2.jpg" class="img-swiper"/>
                    <div class="description-job">
                        <h2>Job :
                        </h2>
                        <h3 class="job">
                            Sponsorship, Media Partner, Events, Media Placement, Digital Campaign, Brand
                            Activities, Sales Leverage
                        </h3>
                        <hr class="line-section"/>
                        <h2>Brand :
                        </h2>
                        <h4 class="desc">
                            Yamaha, Pejaten Village, Labels, Restaurants, Clothes, Insurance, 30 Media
                            partners, in 5 cities, Gala Premiere, Press Screening, Nobar,Meet and Greet,
                            Talkshow, Interview, 4 Days Event
                        </h4>
                    </div>
                </div>

            </swiper-slide>
            <swiper-slide>
                <div class="swip-con">
                    <img src="../assets/portofolio/port3.jpg" class="img-swiper"/>
                    <div class="description-job">
                        <h2>Job :
                        </h2>
                        <h3 class="job">
                            Sponsorship, Media Placement, Digital Campaign, Brand Activities, Sales Leverage
                        </h3>
                        <hr class="line-section"/>
                        <h2>Brand :
                        </h2>
                        <h4 class="desc">
                            Huawei, Mercy, Jaguar, Metrox, Gala Premiere, Press Screening, Nobar,Meet and
                            Greet, Talkshow, Interview, Roadshow
                        </h4>
                    </div>
                </div>

            </swiper-slide>
            <swiper-slide>
                <div class="swip-con">
                    <img src="../assets/portofolio/port4.jpg" class="img-swiper"/>
                    <div class="description-job">
                        <h2>Job :
                        </h2>
                        <h3 class="job">
                            Sponsorship
                        </h3>
                        <hr class="line-section"/>
                        <h2>Brand :
                        </h2>
                        <h4 class="desc">
                            Berniaga.com, Kacang Garuda, Hotels for Roadshow
                        </h4>
                    </div>
                </div>

            </swiper-slide>
            <swiper-slide>
                <div class="swip-con">
                    <img src="../assets/portofolio/port5.jpg" class="img-swiper"/>
                    <div class="description-job">
                        <h2>Job :
                        </h2>
                        <h3 class="job">
                            Sponsorship, Media Partner, Events, Media Placement, Digital Campaign, Brand
                            Activities, Sales Leverage
                        </h3>
                        <hr class="line-section"/>
                        <h2>Brand :
                        </h2>
                        <h4 class="desc">
                            Ayana Hotel and Resort Bali, Rock Bar, Max One, Citilink, Audi
                        </h4>
                    </div>
                </div>

            </swiper-slide>
            <swiper-slide>
                <div class="swip-con">
                    <img src="../assets/portofolio/port6.jpg" class="img-swiper"/>
                    <div class="description-job">
                        <h2>Job :
                        </h2>
                        <h3 class="job">
                            Sponsorship, Media Partner, Events, Media Placement, Digital Campaign, Brand
                            Activities, Sales Leverage
                        </h3>
                        <hr class="line-section"/>
                        <h2>Brand :
                        </h2>
                        <h4 class="desc"></h4>
                    </div>
                </div>
            </swiper-slide>

            <div class="swiper-pagination" slot="pagination"></div>
            <div class="swiper-button-prev" slot="button-prev"></div>
            <div class="swiper-button-next" slot="button-next"></div>
        </swiper>
    </div>
</template>
<style lang="scss" scoped="scoped">
    @import './style/swiper.css';
    .swiper {
        width: 100%;
        height: 1000px;
        color: #ffffff;
    }
    .swip-con {
        width: 100%;
    }
    .swiper-slide {
        text-align: center;
        font-size: 18px;
        // background: #fff;

        /* Center slide text vertically */
        display: -webkit-box;
        display: -ms-flexbox;
        display: -webkit-flex;
        display: flex;
        -webkit-box-pack: center;
        -ms-flex-pack: center;
        -webkit-justify-content: center;
        justify-content: center;
        -webkit-box-align: center;
        -ms-flex-align: center;
        -webkit-align-items: center;
        align-items: center;
    }
</style>
<script>
    import {Swiper, SwiperSlide} from 'vue-awesome-swiper'
    //   import 'swiper/css/swiper.css'
    export default {
        name: 'SwiperPorto',
        components: {
            Swiper,
            SwiperSlide
        },
        data() {
            return {
                swiperOption: {
                    slidesPerView: 1,
                    spaceBetween: 50,
                    autoplay: {
                        delay: 2500,
                        disableOnInteraction: false
                    },

                    pagination: {
                        el: '.swiper-pagination',
                        clickable: true
                    },
                    navigation: {
                        nextEl: '.swiper-button-next',
                        prevEl: '.swiper-button-prev'
                    }
                }
            }
        }
    }
</script>