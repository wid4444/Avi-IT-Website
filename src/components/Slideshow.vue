<!-- <template>
  hard scaping
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>

</style> -->

<template>
    <div class="slide-show">
    <swiper :navigation="true" :modules="modules" class="mySwiper">
      <swiper-slide><img src="../assets/logo.png" alt=""></swiper-slide>
    <swiper-slide>Slide 2</swiper-slide>
      <swiper-slide><img src="../assets/main.jpg" alt=""></swiper-slide>
    <swiper-slide>Slide 4</swiper-slide>
      <swiper-slide>Slide 5</swiper-slide>
      <swiper-slide>Slide 6</swiper-slide>
      <swiper-slide>Slide 7</swiper-slide>
      <swiper-slide>Slide 8</swiper-slide>
      <swiper-slide>Slide 9</swiper-slide>
    </swiper>
</div>
  </template>

  
  <script>
  // Import Swiper Vue.js components
  import { Swiper, SwiperSlide } from "swiper/vue";
  
  // Import Swiper styles
  import "swiper/css";
  
  import "swiper/css/navigation";
  
//   import "./style.css";
  
  // import required modules
  import { Navigation } from "swiper";
  
  export default {
    components: {
      Swiper,
      SwiperSlide,
    },
    setup() {
      return {
        modules: [Navigation],
      };
    },
  };
  </script>

<style lang="scss" scoped>
.slide-show {
    border: solid black 3px;
    margin: 40px  80px;
    border-radius: 20px;
    background: green;
    
    display: flex;
    justify-content: center;
    align-items: center;
}

</style>