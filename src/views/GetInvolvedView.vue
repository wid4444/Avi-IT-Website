<template>
  <div class="involved">

    <div class="donate-money">

      <h3>Make a monetary donation:</h3>
      <iframe id="degives" src="https://www.degives.org/fundraisers/avi-it-on-degives-org/embed"></iframe>


      <div class="social">

        <a href="https://www.paypal.me/aviitcodeforfree">
          <img class="image-p" src="../assets/paypal.png" alt="pay-pal"></a>
        <div class="social-pay"><strong>@aviitcodeforfree</strong></div>

        <a href="https://cash.app/$Aviitcodeforfree">
          <img class="image-c" src="../assets/cashapp.svg.png" alt="cash-app"></a>
        <div class="social-cash"><strong>$Aviitcodeforfree</strong> </div>

      </div>
    </div>

    <div class="head">
      <h3>Thank You!</h3>
      <img id="school" src="../assets/school.jpeg" alt="school">
      <!-- <a class="button" href="https://forms.gle/euPNrYxJxLQiHyEX9 ">Volunteer</a> -->
    </div>

    <div class="donate-tech">
      <h3>Donate technology in any condition:</h3>

      <h4>“We collect old/used devices, fix them up, and give them to people in need or use them during our programs! We
        accept items in any condition, as well as parts.”</h4>
      <img class="repair" src="../assets/IMG_1835.jpg" alt="">
      <a class="button"
        href="https://docs.google.com/forms/d/e/1FAIpQLSeJXN6luQne7eWeqi1s0aUyMEuUMegWM2WMrs9U2ysrvSGXoQ/viewform ">Tech
        Drive Donation</a>
    </div>

    <div class="head">
      <h3>Volunteer:</h3>
      <img id="volunteer" src="../assets/volunteer.jpg" alt="volunteer">
      <a class="button" href="https://forms.gle/euPNrYxJxLQiHyEX9 ">Volunteer</a>
    </div>

    <div class="head">
      <h3>Merch: When you purchase merch, a portion of the cost is donated to us!</h3>
      <img id="merch" src="../assets/IMG_1414.jpg" alt="merch">
      <a class="button" href="https://www.bonfire.com/store/avi-it-merch/ ">Buy now!</a>
    </div>

  </div>




</template>

<script>
export default {

}
</script>

<style scoped lang="scss">
* {
  margin: 0;
  padding: 0;
  list-style: none;
  text-decoration: none;
  font-family: 'Montserrat', sans-serif;
}

.involved {
  background: #bde0fe;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

.donate-money {
  background: #bde0fe;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  background: #3a88e2;
  border-radius: 20px;
  padding: 20px;
  color: white;
}

.donate-money h3 {
  margin-bottom: 20px;

}

#degives {
  max-width: 100%;
  width: 700px;
  height: 600px;
  border: 0;
}

.social {
  background: #bde0fe;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  margin: 10px;
  padding: 15px;
  font-size: 20px;
  border-radius: 15px;
  color: black;
}

.social-pay {
  margin: 20px;
}

.image-p {
  width: 40px;
  height: 40px;
  border-radius: 50%;
  border: 2px solid blue;
}

.image-c {
  width: 40px;
  height: 40px;
  border-radius: 50%;
  border: 2px solid green;
}

.social-cash {
  margin: 20px;
}

.donate-tech {
  background: #bde0fe;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  margin: 20px;
  background: #3a88e2;
  border-radius: 20px;
  padding: 20px;
  color: white;
  text-align: center;
}

.donate-tech h4 {
  margin-bottom: 20px;
  background: #F45B69;
  border-radius: 20px;
  padding: 15px;
  color: rgb(77, 2, 2);
  text-align: center;
}

.donate-tech img {
  width: 100%;
  height: auto;
  border-radius: 15px;
}

.head {
  background: #bde0fe;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  margin: 20px;

  background: #3a88e2;
  border-radius: 20px;
  padding: 20px;
  color: white;
}

.head h3 {
  text-align: center;
  margin-bottom: 20px;
}

h3 {
  background: #3a88e2;
  border-radius: 20px;
  padding: 15px;
  color: white;
  margin-bottom: 20px;
}

#volunteer {
  max-width: 100%;
  height: auto;
  border-radius: 20px;


}

#merch {
  max-width: 100%;
  height: auto;
  border-radius: 20px;
}
#school {
  max-width: 100%;
  width: 1300px;
  height: auto;
  border-radius: 20px;
}

.button {
  margin: 35px 20px 20px;
  padding: 5px 15px;
  text-align: center;
  text-decoration: none;
  transition: 0.5s;
  background-size: 200% auto;
  color: white;
  border-radius: 30px;
  display: block;
  border: 1px solid red;
  font-weight: 700;
  font-size: 25px;
  box-shadow: 0px 0px 14px -7px green;
  background-image: linear-gradient(45deg, #fc2033 0%, #f19901 51%, #fc2033 100%);
  cursor: pointer;
  user-select: none;
  -webkit-user-select: none;
  touch-action: manipulation;

}

.button:hover {
  margin-top: 20px;
  font-weight: 700;
  background-position: right center;
  color: white;
  font-size: 26px;
  text-decoration: none;
}
</style>