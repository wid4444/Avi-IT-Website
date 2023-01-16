<template>
  <div class="software">

    <div class="technicians">

      <img class="repair-center" src="../assets/TheRepairCenter.png" alt="">

      <div class="head"> Our repair technicians are our students who are training with us to enter the field!
        Inquire here if you are in need of our repair services or want to become a technician.:</div>

      <a class="button"
        href="https://docs.google.com/forms/d/e/1FAIpQLSdV25IH1k4i_jZOOwz4GYC-8QtSPTbIcy8JyLXnxjWujRU-zA/viewform">Inquire
        Here!</a>

      <div class="prices">
        <div class="head">Check out our price sheet: </div>
        <a class="button"
          href="https://docs.google.com/document/d/15G2_MxUfT1MF81IUl3GcpIzewPy2isldZGe1XAEtGr0/edit?usp=sharing ">Check
          Price</a>

      </div>
    </div>

    <div class="development">

      <div class="head"> Digital marketing and website development at an affordable price!
        Here at Avi I.T., we strive to help local/small businesses thrive by offering low cost website development and
        management, social media managing/marketing, online advertisement, commercials, and graphic design such as
        logos. Our design team is made up of people in the community and our students. So, when you do business with us,
        you do business with the community!
        To schedule a free consultation, or to find out more about our services and prices go here:</div>

      <a class="button"
        href="https://docs.google.com/forms/d/e/1FAIpQLSf8uUaSWvmXtTgLekl-3_f7wTMmIayvCGwEwt09oK2mxZqI0w/viewform ">Schedule
        Now!</a>
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

.head {
  font-size: 20px;
  margin: 20px;
  text-align: center;
}

.software {
  background: #bde0fe;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

.technicians {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  margin: 20px;
  background: #ff0091;
  border-radius: 25px;
  color: #bde0fe;
  padding: 20px;
  max-width: 100%;
}

.prices {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  background: #ff0091;
  border-radius: 25px;
  color: #bde0fe;
  max-width: 100%;
}

.repair-center {
  max-width: 100%;
  height: auto;
  border-radius: 15px;
}

.development {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  margin: 20px;
  text-align: center;
  background: #ff0091;
  border-radius: 25px;
  color: #bde0fe;
  padding: 20px;
}

.button {
  margin: 20px;
  padding: 5px 15px;
  text-align: center;
  text-decoration: none;
  transition: 0.5s;
  background-size: 200% auto;
  color: white;
  border-radius: 30px;
  display: block;
  border: 1px solid purple;
  font-weight: 700;
  font-size: 20px;
  box-shadow: 0px 0px 14px -7px orange;
  background-image: linear-gradient(45deg, #7209b7 0%, #4895ef 51%, #7209b7 100%);
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
  font-size: 25px;
  text-decoration: none;
}

.button:active {
  transform: scale(0.95);
}
</style>