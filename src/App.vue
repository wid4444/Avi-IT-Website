<template>
  
      <header-menu/>

<main>
  <router-view />
</main>

  <footer-menu/>

</template>


<script>

import FooterMenu from './components/FooterMenu.vue'
import HeaderMenu from './components/HeaderMenu.vue'

export default {

  components: {
     
    FooterMenu,
    HeaderMenu,
    
  },

}

</script>


<style scoped lang="scss">

@import url('https://fonts.googleapis.com/css2?family=Montserrat&display=swap');

</style>
