<template>

  <div class="events">

    <div class="upcoming-events">
    <iframe src="https://calendar.google.com/calendar/embed?height=400&wkst=1&bgcolor=%23ffffff&ctz=America%2FNew_York&showNav=1&mode=MONTH&title=Avi%20I.T.%20Events&src=YXZpLml0LmNvZGUuZm9yLmZyZWVAZ21haWwuY29t&src=ZW4udXNhI2hvbGlkYXlAZ3JvdXAudi5jYWxlbmRhci5nb29nbGUuY29t&color=%23D81B60&color=%230B8043" style="border:solid 1px #777" width="100%" height="450" frameborder="0" scrolling="no"></iframe>
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
.upcoming-events {
  position: relative;
  overflow: hidden;
  max-width: 100%;
  width: 1200px;
  height: auto;
  border-radius: 15px;
  // margin: 20px;
  // padding: 40px;
  // background: rgb(241, 52, 241);
  border: solid 1px rgb(75, 74, 74);
}
.events {
  background: #bde0fe;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  max-width: 100%;

}

.donate-money {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  border-radius: 20px;
  padding: 20px;
}

#degives {
  width: 300%;
  height: 600px;
  border: 0;
}

@media screen and (max-width:700px) {

  #degives {
    width: 100%;
    height: 500px;
    border: 0;
  }
  .upcoming-events {
    margin: 20px;
  }
}
</style>