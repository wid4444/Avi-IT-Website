<template>

  <div class="courses">

    <!-- <div class="upcoming-events">
      <iframe class="calendar" allowfullscreen
        src="https://calendar.google.com/calendar/embed?height=400&wkst=1&bgcolor=%23ffffff&ctz=America%2FNew_York&showNav=1&mode=MONTH&title=Avi%20I.T.%20Events&src=YXZpLml0LmNvZGUuZm9yLmZyZWVAZ21haWwuY29t&src=ZW4udXNhI2hvbGlkYXlAZ3JvdXAudi5jYWxlbmRhci5nb29nbGUuY29t&color=%23D81B60&color=%230B8043"
        style="border:solid 1px #777" frameborder="0" scrolling="no"></iframe>
    </div> -->


    <div class="books">
      <h3>Book Courses</h3>

      <div class="book-courses">
        <img class="clase" src="../assets/course.jpeg" alt="clase">
      </div>

      <div class="course-list">
        <li>
          <a class="button" id="list"
            href="https://docs.google.com/document/d/1FRAf9h92oc5r7-2pRoepBGioMrotkO1zqu94jHfYr_M/edit ">Course List</a>
        </li>
        <li>
          <a class="button" id="book" href=" https://forms.gle/iAjSuzY6qGGBgc8g8 ">English</a>
        </li>
      </div>
    </div>


    <div class="books">
      <h3>Cursos en Español</h3>
      <div class="book-courses">
        <img class="clase" src="../assets/clase.jpeg" alt="clase">
      </div>

      <div class="course-list">
        <li>
          <a class="button" id="list"
            href="https://docs.google.com/document/d/1FRAf9h92oc5r7-2pRoepBGioMrotkO1zqu94jHfYr_M/edit ">Lista de
            Cursos</a>
        </li>
        <li>
          <a class="button" id="book" href="https://forms.gle/y2naR5caKMpofEqDA">Español</a>
        </li>
      </div>
    </div>




    <div class="comp-tia">
      <iframe class="tia"
        src="https://docs.google.com/presentation/d/e/2PACX-1vREtw0JhEccm_-YF37XXJwT1UUT7aVfWXj4Q-wWembaqfwMrRIz9fF8q19mIMtZ_U1T1-53gO0gEk7_/embed?start=true&loop=false&delayms=5000"></iframe>
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

.courses {
  background: #bde0fe;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

.upcoming-events {
  position: relative;
  overflow: hidden;
  width: 100%;
  padding-top: 56.25%;
}

.calendar {
  width: 100%;
  height: 100%;
  position: absolute;
  bottom: 0;
  border-radius: 15px;
}

.course-list {
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
}

.button {
  margin: 30px 20px 20px;
  padding: 5px 15px;
  text-align: center;
  text-decoration: none;
  transition: 0.5s;
  background-size: 200% auto;
  color: white;
  border-radius: 30px;
  display: block;
  border: 1px solid rgb(245, 4, 237);
  font-weight: 700;
  font-size: 20px;
  box-shadow: 0px 0px 14px -7px green;
  background-image: linear-gradient(45deg, #fe5d9f 0%, #f4bbd3 51%, #fe5d9f 100%);
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

.books {
  max-width: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  margin: 20px;
  background: rgb(56, 190, 54);
  border-radius: 20px;
  padding: 20px;
  color: #007f5f;
}

.books h3 {
  background: rgb(56, 190, 54);
  border-radius: 20px;
  padding: 10px;
  margin: 15px 15px 30px;
  color: rgb(201, 246, 175);
}

.clase {
  max-width: 100%;
  height: auto;
  border-radius: 15px;
}

.comp-tia {
  background: #bde0fe;
  position: relative;
  overflow: hidden;
  width: 85%;
  padding-top: 56.25%;
  margin: 20px;
}

.tia {
  width: 100%;
  height: 100%;
  position: absolute;
  bottom: 0;
  border-radius: 15px;
}
</style>