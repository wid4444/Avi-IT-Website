

<!-- <template>
    <div class="slide-show">
    <swiper :navigation="true" :modules="modules" class="mySwiper">
      <swiper-slide><img src="../assets/Gallery/Soiree/1-102.jpg" alt=""></swiper-slide>
      <swiper-slide><img src="../assets/Gallery/Soiree/1-105.jpg" alt=""></swiper-slide>
      <swiper-slide><img src="../assets/Gallery/Soiree/1-104.jpg" alt=""></swiper-slide>
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
  </script> -->

<style lang="scss" scoped>
.slide-show {
    border: solid black 1px;
    margin: 40px  80px;
    border-radius: 20px;
    // background: green;
    
    display: flex;
    justify-content: center;
    align-items: center;
    max-width: 100%;
    width: 1300px;
    // height: 803px;
}
 img {
  max-width: 1300px;
  height: 803px;
  border-radius: 20px;

}
@media screen and (max-width:1400px) {
  .slide-show {
    max-width: 100%;
  width: 700px;
  }
  .slide-show img {
  max-width: 100%;
  width: 700px;
  height: 432px;

}

}
@media screen and (max-width:700px) {
  .slide-show {
    max-width: 100%;
  width: 400px;
  }
  .slide-show img {
  max-width: 100%;
  width: 400px;
  height: 247px;

}
}

</style>




<template>
  <div class="slide-show">
  <swiper
    :spaceBetween="30"
    :effect="'fade'"
    :navigation="true"
    :pagination="{
      clickable: true,
    }"
    :modules="modules"
    class="mySwiper"
  >
    <swiper-slide><img src="../assets/Gallery/Soiree/1-12.jpg" alt=""></swiper-slide>
    <swiper-slide><img src="../assets/Gallery/Soiree/1-94.jpg" alt=""></swiper-slide>
    <swiper-slide><img src="../assets/Gallery/Soiree/1-98.jpg" alt=""></swiper-slide>
    <swiper-slide><img src="../assets/Gallery/Soiree/1-99.jpg" /></swiper-slide>
    <swiper-slide><img src="../assets/Gallery/Soiree/1-109.jpg" /></swiper-slide>
    <swiper-slide><img src="../assets/Gallery/Soiree/1-117.jpg" /></swiper-slide>
    <swiper-slide><img src="../assets/Gallery/Soiree/1-131.jpg" /></swiper-slide>
    <swiper-slide><img src="../assets/Gallery/Soiree/1-135.jpg" /></swiper-slide>
    <swiper-slide><img src="../assets/Gallery/Soiree/1-139.jpg" /></swiper-slide>
    <swiper-slide><img src="../assets/Gallery/Soiree/1-153.jpg" /></swiper-slide>
    <swiper-slide><img src="../assets/Gallery/Soiree/1-154.jpg" /></swiper-slide>
    <swiper-slide><img src="../assets/Gallery/Soiree/1-177.jpg" /></swiper-slide>
    <swiper-slide><img src="../assets/Gallery/Soiree/1-181.jpg" /></swiper-slide>
    <swiper-slide><img src="../assets/Gallery/Soiree/1-182.jpg" /></swiper-slide>
    <swiper-slide><img src="../assets/Gallery/Soiree/1-185.jpg" /></swiper-slide>
    <swiper-slide><img src="../assets/Gallery/Soiree/1-205.jpg" /></swiper-slide>
    <swiper-slide><img src="../assets/Gallery/Soiree/1-5.jpg" /></swiper-slide>
    <swiper-slide><img src="../assets/Gallery/Soiree/1-6.jpg" /></swiper-slide>
    <swiper-slide><img src="../assets/Gallery/Soiree/1-23.jpg" /></swiper-slide>
    <swiper-slide><img src="../assets/Gallery/Soiree/1-24.jpg" /></swiper-slide>
    <swiper-slide><img src="../assets/Gallery/Soiree/1-25.jpg" /></swiper-slide>
    <swiper-slide><img src="../assets/Gallery/Soiree/1-26.jpg" /></swiper-slide>
    <swiper-slide><img src="../assets/Gallery/Soiree/1-27.jpg" /></swiper-slide>
    <swiper-slide><img src="../assets/Gallery/Soiree/1-29.jpg" /></swiper-slide>
    <swiper-slide><img src="../assets/Gallery/Soiree/1-32.jpg" /></swiper-slide>
    <swiper-slide><img src="../assets/Gallery/Soiree/1-33.jpg" /></swiper-slide>
    <swiper-slide><img src="../assets/Gallery/Soiree/1-34.jpg" /></swiper-slide>
    <swiper-slide><img src="../assets/Gallery/Soiree/1-37.jpg" /></swiper-slide>
    <swiper-slide><img src="../assets/Gallery/Soiree/1-41.jpg" /></swiper-slide>
    <swiper-slide><img src="../assets/Gallery/Soiree/1-47.jpg" /></swiper-slide>
    <swiper-slide><img src="../assets/Gallery/Soiree/1-51.jpg" /></swiper-slide>
    <swiper-slide><img src="../assets/Gallery/Soiree/1-56.jpg" /></swiper-slide>
    <swiper-slide><img src="../assets/Gallery/Soiree/1-60.jpg" /></swiper-slide>
    <swiper-slide><img src="../assets/Gallery/Soiree/1-62.jpg" /></swiper-slide>
    <swiper-slide><img src="../assets/Gallery/Soiree/1-63.jpg" /></swiper-slide>
    <swiper-slide><img src="../assets/Gallery/Soiree/1-68.jpg" /></swiper-slide>
    <swiper-slide><img src="../assets/Gallery/Soiree/1-70.jpg" /></swiper-slide>
    <swiper-slide><img src="../assets/Gallery/Soiree/1-71.jpg" /></swiper-slide>
    <swiper-slide><img src="../assets/Gallery/Soiree/1-72.jpg" /></swiper-slide>
    <swiper-slide><img src="../assets/Gallery/Soiree/1-73.jpg" /></swiper-slide>
    <swiper-slide><img src="../assets/Gallery/Soiree/1-76.jpg" /></swiper-slide>
    <swiper-slide><img src="../assets/Gallery/Soiree/1-78.jpg" /></swiper-slide>
    <swiper-slide><img src="../assets/Gallery/Soiree/1-80.jpg" /></swiper-slide>
    <swiper-slide><img src="../assets/Gallery/Soiree/1-81.jpg" /></swiper-slide>
    <swiper-slide><img src="../assets/Gallery/Soiree/1-82.jpg" /></swiper-slide>
    <swiper-slide><img src="../assets/Gallery/Soiree/1-83.jpg" /></swiper-slide>
    <swiper-slide><img src="../assets/Gallery/Soiree/1-94.jpg" /></swiper-slide>
    <swiper-slide><img src="../assets/Gallery/Soiree/1-113.jpg" /></swiper-slide>
    <swiper-slide><img src="../assets/Gallery/Soiree/1-121.jpg" /></swiper-slide>
    <swiper-slide><img src="../assets/Gallery/Soiree/1-125.jpg" /></swiper-slide>
    <swiper-slide><img src="../assets/Gallery/Soiree/1-141.jpg" /></swiper-slide>
    <swiper-slide><img src="../assets/Gallery/Soiree/1-142.jpg" /></swiper-slide>
    <swiper-slide><img src="../assets/Gallery/Soiree/1-143.jpg" /></swiper-slide>
    <swiper-slide><img src="../assets/Gallery/Soiree/1-144.jpg" /></swiper-slide>
    <swiper-slide><img src="../assets/Gallery/Soiree/1-145.jpg" /></swiper-slide>
    <swiper-slide><img src="../assets/Gallery/Soiree/1-146.jpg" /></swiper-slide>
    <swiper-slide><img src="../assets/Gallery/Soiree/1-149.jpg" /></swiper-slide>
    <swiper-slide><img src="../assets/Gallery/Soiree/1-152.jpg" /></swiper-slide>
    <swiper-slide><img src="../assets/Gallery/Soiree/1-157.jpg" /></swiper-slide>





    </swiper>
  </div>


</template>

<script>
// Import Swiper Vue.js components
import { Swiper, SwiperSlide } from "swiper/vue";

// Import Swiper styles
import "swiper/css";

import "swiper/css/effect-fade";
import "swiper/css/navigation";
import "swiper/css/pagination";

// import "./style.css";

// import required modules
import { EffectFade, Navigation, Pagination } from "swiper";

export default {
  components: {
    Swiper,
    SwiperSlide,
  },
  setup() {
    return {
      modules: [EffectFade, Navigation, Pagination],
    };
  },
};
</script>

<!-- <style scoped lang="scss">
.slide-show img {
  max-width: 100%;
  width: 1300px;
  height: 850px;

}

@media screen and (max-width:1800px) {
  .slide-show img {
  max-width: 100%;
  width: 700px;
  height: 432px;

}

}
@media screen and (max-width:700px) {
  .slide-show img {
  max-width: 100%;
  width: 1300px;
  height: 850px;

}
}

</style> -->