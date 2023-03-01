<template>
  <footer class="footer">

    <div class="news-letter">
      <a href="https://docs.google.com/forms/d/e/1FAIpQLSd3DFSNiqUDytVyfgLVJDzc6gjUXLAUEMw-NVQ1RMnA-G05dw/viewform"
        class="button">Join Our Newsletter!</a>
    </div>

    <div class="info">
      <h2>
        Avi I.T. Inc.
      </h2>
      <p> <strong> (302) 268-6649 | Contact@avi-it.org </strong></p>
    </div>

    <div class="icons">
      <ul>
        <li><a href="https://www.facebook.com/CodeAvi.I.T/?ref=page_internal"><i class="fab fa-facebook"
              aria-hidden="true"></i></a></li>
        <li><a href="https://www.youtube.com/channel/UCsiopc3vV09YzHZqVeP5ylw"><i class="fab fa-youtube"
              aria-hidden="true"></i></a></li>
        <li><a href="https://www.linkedin.com/in/avi-i-t-b82058236"><i class="fab fa-linkedin"
              aria-hidden="true"></i></a></li>
        <li><a href="https://www.instagram.com/avi_i.t/?hl=en"><i class="fab fa-instagram" 
              aria-hidden="true"></i></a>
        </li>
        <!-- <li><a href="#"><i class="fab fa-twitter" aria-hidden="true"></i></a></li> -->
      </ul>
      <div class="made-by">
        
        <p><i id="c" class="fa-regular fa-copyright"></i> &nbsp;Copyright 2023 Avi I.T. LLC <br>
          All Rights Reserved <br> This website was designed and build by Leobardo D. Martinez-Quiroz</p>
       </div>
    </div>

  </footer>
</template>

<script>
export default {

}
</script>

<style scoped lang="scss">
.footer {
  position: absolute;
  background: #bde0fe;
  display: flex;
  flex-direction: column;
  justify-content: space-around;
  align-items: center;
  color: green($color: #000000);
  position: static;
  bottom: 0;
  width: auto;

}

.info {
  background: #bde0fe;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: space-around;
  margin-bottom: 40px;
  font-family: 'Montserrat', sans-serif;
}

.news-letter {
  margin-top: 30px;
  font-family: 'Montserrat', sans-serif;
}

.button {
  margin: 10px;
  padding: 15px 30px;
  text-align: center;
  text-transform: uppercase;
  text-decoration: none;
  transition: 0.5s;
  background-size: 200% auto;
  color: white;
  border-radius: 30px;
  display: block;
  border: 1px solid purple;
  font-weight: 700;
  box-shadow: 0px 0px 14px -7px #b100e8;
  background-image: linear-gradient(45deg, #6a00f4 0%, #b100e8 51%, #6a00f4 100%);
  cursor: pointer;
  user-select: none;
  -webkit-user-select: none;
  touch-action: manipulation;
}

.button:hover {
  background-position: right center;
  color: #fff;
  text-decoration: none;
  font-size: 20px;
}

.button:active {
  transform: scale(0.95);
}

// Social Media Icons

ul {
  position: relative;
  top: -20%;
  left: 45%;
  transform: translate(-50%, -50%);
  display: flex;
}

ul li {
  list-style: none;
}

ul li a {
  position: relative;
  width: 60px;
  height: 60px;
  display: block;
  text-align: center;
  margin: 0 10px;
  border-radius: 50%;
  padding: 6px;
  box-sizing: border-box;
  text-decoration: none;
  box-shadow: 0 10px 15px rgba(0, 0, 0, 0.3);
  background: linear-gradient(0deg, #ddd, #fff);
  transition: .5s;
}

ul li a:hover {
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.3);
  text-decoration: none;
}

ul li a .fab {
  width: 100%;
  height: 100%;
  display: block;
  background: linear-gradient(0deg, #fff, #ddd);
  border-radius: 50%;
  line-height: calc(60px - 12px);
  font-size: 24px;
  color: #262626;
  transition: .5s;
}

ul li:nth-child(1) a:hover .fab {
  color: #3b5998;
}

ul li:nth-child(2) a:hover .fab {
  color: red;
}

ul li:nth-child(3) a:hover .fab {
  color: #007bb6;
}

ul li:nth-child(4) a:hover .fab {
  color: #c42c9d;
}

// in case there is a twitter
ul li:nth-child(5) a:hover .fab {
  color: #3f8efc;
}

.made-by {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  margin-bottom: 30px;
  font-family: 'Montserrat', sans-serif;
  font-size: 12px;
  text-align: center;
}
#c {
  font-size: 10px;
}
</style>