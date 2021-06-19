<template>
  <div class="swiper-porto">
    <swiper class="swiper" :options="swiperOption">
      <swiper-slide>
        <div class="swip-con">
          <img src="https://i.ibb.co/Cwq42Dn/port1.jpg" class="img-swiper" />

          <div class="description-job">
            <h2>Job :</h2>
            <h3 class="job">
         Job 1
            </h3>
            <hr class="line-section" />
            <h2>Brand :</h2>
            <h4 class="desc">
             Brand 1
            </h4>
          </div>
        </div>
      </swiper-slide>
      <swiper-slide>
        <div class="swip-con">
          <img src="https://i.ibb.co/qFHVXKN/port2.jpg" class="img-swiper" />

          <div class="description-job">
            <h2>Job :</h2>
            <h3 class="job">
            Job 2
            </h3>
            <hr class="line-section" />
            <h2>Brand :</h2>
            <h4 class="desc">
            Brand 2
            </h4>
          </div>
        </div>
      </swiper-slide>
      <swiper-slide>
        <div class="swip-con">
          <img src="https://i.ibb.co/b1dz3bp/port3.jpg" class="img-swiper" />

          <div class="description-job">
            <h2>Job :</h2>
            <h3 class="job">
         Job 3
            </h3>
            <hr class="line-section" />
            <h2>Brand :</h2>
            <h4 class="desc">
            Brand 3
            </h4>
          </div>
        </div>
      </swiper-slide>
      <swiper-slide>
        <div class="swip-con">
          <img src="https://i.ibb.co/bdRGQL1/port4.jpg" class="img-swiper" />

          <div class="description-job">
            <h2>Job :</h2>
            <h3 class="job">
Job 4            </h3>
            <hr class="line-section" />
            <h2>Brand :</h2>
            <h4 class="desc">
Brand 4            </h4>
          </div>
        </div>
      </swiper-slide>
      <swiper-slide>
        <div class="swip-con">
          <img src="https://i.ibb.co/4Ywv9dk/port5.jpg" class="img-swiper" />

          <div class="description-job">
            <h2>Job :</h2>
            <h3 class="job">
              Job 5
            </h3>
            <hr class="line-section" />
            <h2>Brand :</h2>
            <h4 class="desc">
Brand 5            </h4>
          </div>
        </div>
      </swiper-slide>
      <swiper-slide>
        <div class="swip-con">
          <img src="https://i.ibb.co/5cQ6sTJ/port6.jpg" class="img-swiper" />

          <div class="description-job">
            <h2>Job :</h2>
            <h3 class="job">
              Job 6
            </h3>
            <hr class="line-section" />
            <h2>Brand :</h2>
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
<script>
import "swiper/dist/css/swiper.css";
import { swiper, swiperSlide } from "vue-awesome-swiper";

import "../assets/style/swiper.css";
export default {
  name: "SwiperPorto",
  components: {
    swiper,
    swiperSlide
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
          el: ".swiper-pagination",
          clickable: true
        },
        navigation: {
          nextEl: ".swiper-button-next",
          prevEl: ".swiper-button-prev"
        }
      }
    };
  }
};
</script>
<style scoped="scoped">
@import "../assets/style/swiper.css";
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
.swiper-container {
  height: 450px;
  width: 100%;
}
</style>
