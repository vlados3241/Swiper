<template>
  <div class="swiper-box">
    <swiper 
      :slides-per-view="1" 
      :space-between="10" 
      :loop="true"
      :navigation="true"
      :pagination="true">
    <swiper-slide>
      <img src="/Img/Group 7.jpg" alt="Изображение 1" />
    </swiper-slide>
    <swiper-slide>
      <img src="/Img/Group 15.jpg" alt="Изображение 2" />
    </swiper-slide>
    <swiper-slide>
      <img src="/Img/Group 17.svg" alt="Изображение 3" />
    </swiper-slide>
  </swiper>
  </div>
</template>

<script>
import { Swiper, SwiperSlide } from 'swiper/vue';
import 'swiper/swiper-bundle.css';

export default {
  components: {
    Swiper,
    SwiperSlide
  }
}
</script>

<style>
.swiper-box{
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  height: 100vh;
}
.swiper-slide{
  display: flex;
  justify-content: center;
}
</style>