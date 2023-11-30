<template>
  <div class="home">

    <div class="img-container">

      <div class="mission-statement">

        <strong>
          <h2>"Establishing a foundation for computer science education among all
            backgrounds and experiences in
            order to mitigate the diversity gap in the computer science field and alleviate
            the digital divide."</h2>
        </strong>

      </div>
    </div>

    <div class="slideshow">
      <div class="entire-content">
        <div class="content-carrousel">
          <figure class="shadow"><img src="../assets/slideshow/avi1.jpg" /></figure>
          <figure class="shadow"><img src="../assets/slideshow/avi2.jpg" /></figure>
          <figure class="shadow"><img src="../assets/slideshow/avi3.jpg" /></figure>
          <figure class="shadow"><img src="../assets/slideshow/avi4.jpeg" /></figure>
          <figure class="shadow"><img src="../assets/slideshow/avi5.jpg" /></figure>
          <figure class="shadow"><img src="../assets/slideshow/avi6.jpg" /></figure>
          <figure class="shadow"><img src="../assets/slideshow/avi7.jpg" /></figure>
          <figure class="shadow"><img src="../assets/slideshow/avi8.jpg" /></figure>
          <figure class="shadow"><img src="../assets/slideshow/avi0.png" /></figure>
        </div>
      </div>

    </div>
    <div class="link">
      <router-link class="gallery" to="/gallery">Gallery</router-link>
    </div>

    <iframe class="video" src="https://youtu.be/sN2KqUWnX8g?feature=shared" title="YouTube video player" frameborder="0"
      allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen>
    </iframe>
  <img class="main-picture" src="../assets/OurSolution.jpeg" alt="main-picture">
    <img class="main-picture" src="../assets/OurSolution2.jpeg" alt="main-picture">
    <img class="main-picture" src="../assets/OurSolution3.jpeg" alt="main-picture">
    <iframe class="map"
      src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3067.6353164242323!2d-75.5782999851701!3d39.74784197944844!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x89c6fd9fb48e34f9%3A0xd80788eecd90ed87!2s2101%20Lancaster%20Ave%2C%20Wilmington%2C%20DE%2019805!5e0!3m2!1sen!2sus!4v1646194535198!5m2!1sen!2sus"
      style="border:0;" allowfullscreen="" loading="lazy">
    </iframe>

  </div>
</template>


<script>



export default {
  name: 'HomeView',
  components: {

  }
}
</script>

<style scoped lang="scss">
* {
  font-family: 'Montserrat', sans-serif;
}

.home {
  background: #bde0fe;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  min-height: 100vh;
  padding: 20px;
}

.mission-statement h2 {
  text-align: center;
  margin: 20px;
  background: #b100e8;
  color: white;
  border-radius: 20px;
  padding: 15px;
}

.main-picture {
  max-width: 100%;
  width: 1300px;
  height: auto;
  margin: 10px 20px;
  border-radius: 15px;
}

.link {
  background: #bde0fe;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  margin-bottom: 30px;
}

.gallery {
  margin: 20px;
  padding: 5px 15px;
  text-align: center;
  text-decoration: none;
  transition: 0.5s;
  background-size: 200% auto;
  color: white;
  border-radius: 30px;
  display: block;
  border: 1px solid green;
  font-weight: 700;
  font-size: 30px;
  box-shadow: 0px 0px 14px -7px green;
  background-image: linear-gradient(45deg, #29bf12 0%, #abff4f 51%, #29bf12 100%);
  cursor: pointer;
  user-select: none;
  -webkit-user-select: none;
  touch-action: manipulation;

}

.gallery:hover {
  margin-top: 20px;
  font-weight: 700;
  background-position: right center;
  color: white;
  font-size: 35px;
  text-decoration: none;
}

.video {
  max-width: 100%;
  width: 1300px;
  height: 500px;
  margin: 10px 20px;
  border-radius: 15px;
}

.map {
  max-width: 100%;
  width: 1300px;
  height: 400px;
  margin: 10px 20px;
  border-radius: 15px;
}

.slideshow {
  margin: 30px;
  margin-bottom: 40px;
  height: 550px;
  width: 100%;
  box-sizing: border-box;
  overflow: hidden;
  display: flex;
  align-items: flex-start;
  justify-content: center;
}


.entire-content {
  width: 190px;
  height: auto;
  perspective: 1000px;
  position: relative;
  display: flex;
  align-items: center;
  justify-content: center;
}

.content-carrousel {
  width: 130%;
  position: absolute;
  float: right;
  animation: rotar 30s infinite linear;
  transform-style: preserve-3d;
}

.content-carrousel:hover {
  animation-play-state: paused;
  cursor: pointer;
}

.content-carrousel figure {
  width: 100%;
  height: 245px; // To change the size on carousel pictures

  border: 1px solid #3b444b;
  overflow: hidden;
  position: absolute;
}

.content-carrousel figure:nth-child(1) {
  transform: rotateY(0deg) translateZ(400px);
}

.content-carrousel figure:nth-child(2) {
  transform: rotateY(40deg) translateZ(400px);
}

.content-carrousel figure:nth-child(3) {
  transform: rotateY(80deg) translateZ(400px);
}

.content-carrousel figure:nth-child(4) {
  transform: rotateY(120deg) translateZ(400px);
}

.content-carrousel figure:nth-child(5) {
  transform: rotateY(160deg) translateZ(400px);
}

.content-carrousel figure:nth-child(6) {
  transform: rotateY(200deg) translateZ(400px);
}

.content-carrousel figure:nth-child(7) {
  transform: rotateY(240deg) translateZ(400px);
}

.content-carrousel figure:nth-child(8) {
  transform: rotateY(280deg) translateZ(400px);
}

.content-carrousel figure:nth-child(9) {
  transform: rotateY(320deg) translateZ(400px);
}

.content-carrousel figure:nth-child(10) {
  transform: rotateY(360deg) translateZ(400px);
}

.shadow {
  position: absolute;
  box-shadow: 0px 0px 20px 0px #000;
  border-radius: 1px;
}

.content-carrousel img {
  image-rendering: auto;
  transition: all 300ms;
  width: 100%;
  height: auto;
}

.content-carrousel img:hover {
  transform: scale(1.2);
  transition: all 300ms;
}

@keyframes rotar {
  from {
    transform: rotateY(0deg);
  }

  to {
    transform: rotateY(360deg);
  }
}

// Ipad size

@media screen and (max-width:1024px) {


  .slideshow {
    margin: 30px;
    height: 380px;
    width: 100%;
    box-sizing: border-box;
    overflow: hidden;
    display: flex;
    align-items: flex-start;
    justify-content: center;
  }

  .content-carrousel {
    width: 100%;
    position: absolute;
    float: right;
    animation: rotar 30s infinite linear;
    transform-style: preserve-3d;
  }

  .content-carrousel img {
    image-rendering: auto;
    transition: all 300ms;
    width: 100%;
    height: auto;
  }

  .content-carrousel figure {
    width: 100%;
    height: 190px; // To change the size on carousel pictures
    border: 1px solid #3b444b;
    overflow: hidden;
    position: absolute;
  }

  .content-carrousel figure:nth-child(1) {
    transform: rotateY(0deg) translateZ(300px);
  }

  .content-carrousel figure:nth-child(2) {
    transform: rotateY(40deg) translateZ(300px);
  }

  .content-carrousel figure:nth-child(3) {
    transform: rotateY(80deg) translateZ(300px);
  }

  .content-carrousel figure:nth-child(4) {
    transform: rotateY(120deg) translateZ(300px);
  }

  .content-carrousel figure:nth-child(5) {
    transform: rotateY(160deg) translateZ(300px);
  }

  .content-carrousel figure:nth-child(6) {
    transform: rotateY(200deg) translateZ(300px);
  }

  .content-carrousel figure:nth-child(7) {
    transform: rotateY(240deg) translateZ(300px);
  }

  .content-carrousel figure:nth-child(8) {
    transform: rotateY(280deg) translateZ(300px);
  }

  .content-carrousel figure:nth-child(9) {
    transform: rotateY(320deg) translateZ(300px);
  }

  .content-carrousel figure:nth-child(10) {
    transform: rotateY(360deg) translateZ(300px);
  }
}


// Cellphone size

@media screen and (max-width:815px) {

  h2 {
    font-size: 18px;
  }

  .image {
    width: auto;
    height: auto;
  }

  .slideshow {
    margin: 10px;
    height: 190px;
    width: 100%;
    box-sizing: border-box;
    overflow: hidden;
    display: flex;
    align-items: flex-start;
    justify-content: center;
  }

  .content-carrousel {
    width: 50%;
    position: absolute;
    float: right;
    animation: rotar 30s infinite linear;
    transform-style: preserve-3d;
    display: flex;
    justify-content: center;
  }

  .content-carrousel img {
    image-rendering: auto;
    transition: all 300ms;
    width: 100%;
    height: auto;
  }

  .content-carrousel figure {
    width: 100%;
    height: 90px; // To change the size on carousel pictures 

    border: 1px solid #3b444b;
    overflow: hidden;
  }

  .content-carrousel figure:nth-child(1) {
    transform: rotateY(0deg) translateZ(160px);
  }

  .content-carrousel figure:nth-child(2) {
    transform: rotateY(40deg) translateZ(160px);
  }

  .content-carrousel figure:nth-child(3) {
    transform: rotateY(80deg) translateZ(160px);
  }

  .content-carrousel figure:nth-child(4) {
    transform: rotateY(120deg) translateZ(160px);
  }

  .content-carrousel figure:nth-child(5) {
    transform: rotateY(160deg) translateZ(160px);
  }

  .content-carrousel figure:nth-child(6) {
    transform: rotateY(200deg) translateZ(160px);
  }

  .content-carrousel figure:nth-child(7) {
    transform: rotateY(240deg) translateZ(160px);
  }

  .content-carrousel figure:nth-child(8) {
    transform: rotateY(280deg) translateZ(160px);
  }

  .content-carrousel figure:nth-child(9) {
    transform: rotateY(320deg) translateZ(160px);
  }

  .content-carrousel figure:nth-child(10) {
    transform: rotateY(360deg) translateZ(160px);
  }

  .entire-content {
    position: relative;
    display: flex;
    align-items: center;
    justify-content: center;

  }
}
</style>
