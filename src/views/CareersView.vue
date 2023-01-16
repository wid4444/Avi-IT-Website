<template>
  <div class="career">

    <div class="career-center">

      <div class="head">
        Interested in a career in tech? Need help with your small business? Fill out an inquiry below!</div>

      <img id="career" src="../assets/career.png" alt="">

      <a class="button"
        href="https://docs.google.com/forms/d/e/1FAIpQLSfrMCHNVr8zKXbaGQN3Jkuck-rtkXzKvo0YPx-TIHbOr9v2kw/viewform?usp=sf_link">Inquire
        Here!</a>

    </div>

    <div class="internship">

      <div class="head">
        Want to learn technology repair or software development? Intern with us!</div>

      <img id="career" src="../assets/internship.png">

      <a class="button" href="https://docs.google.com/forms/d/e/1FAIpQLSetQbuAgLCaGzbdZieX8JBRSmz768Ajqa_HwRm6jDfJm9ixOw/viewform?usp=sf_link
">Apply Here!</a>
    </div>

    <div class="work-for-us">
      <h2>Work for us (software development, instructor, or repair technician): Email us at Contact@avi-it.org for
        information</h2>
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

.career {
  background: #bde0fe;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  max-width: 100%;

}

.career-center {

  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  margin: 20px;
  margin-bottom: 30px;
  text-align: center;
  padding: 20px;
  background: #7209b7;
  color: #8adef8;
  border-radius: 15px;
}

.internship {

  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  margin: 20px;
  text-align: center;
  padding: 20px;
  background: #7209b7;
  color: #8adef8;
  border-radius: 15px;
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
  border: 0px;
  font-weight: 700;
  font-size: 25px;
  box-shadow: 0px 0px 14px -7px orange;
  background-image: linear-gradient(45deg, #f72585 0%, rgb(212, 0, 255) 51%, #f72585 100%);
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
  font-size: 30px;
  text-decoration: none;
}

.button:active {
  transform: scale(0.95);
}

.work-for-us {
  margin: 20px;
  text-align: center;
  background: rgb(86, 190, 21);
  border-radius: 20px;
  color: green;
  padding: 15px;
}

.head {
  margin-bottom: 20px;
  padding: 20px;
  font-size: 18px;
}

#career {
  max-width: 100%;
  height: auto;
  border-radius: 15px;
}

@media screen and (max-width:700px) {
  .head {
    padding: 15px;
    text-align: center;
  }

  .work-for-us {
    font-size: 12px;
    border-radius: 20px;
    padding: 15px;
  }
}
</style>