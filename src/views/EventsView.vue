<template>

  <div class="events">
    <div class="donate-money">

      <iframe id="degives" src="https://www.degives.org/fundraisers/the-soiree-celebration/embed"
        frameborder="0"></iframe>
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

.events {
  background: #bde0fe;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  max-width: 220%;

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
}
</style>