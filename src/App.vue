<template>
  <NavbarComponent></NavbarComponent>
  <router-view />
  <FooterComponent></FooterComponent>
</template>

<script>
// @ is an alias to /src
import NavbarComponent from '@/components/NavbarComponent.vue'
import FooterComponent from '@/components/FooterComponent.vue'

export default {
  components: {
    NavbarComponent,
    FooterComponent
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Titillium+Web&display=swap');

* {
  box-sizing: border-box;
}

body {
  font-family: 'Titillium Web', sans-serif;
  background-color: #EAFAF1;
  
}
</style>