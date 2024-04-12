<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Header from './components/Header.vue'
import Main from './views/HomeView.vue'
import Footer from './components/Footer.vue'
</script>

<template>
  <Header></Header>
  <Main></Main>
  <Footer></Footer>
  
</template>

<style >
#app {
  color: #1A1A1A;
  font-family: Arial;
  /* background: #5c3c3c; */

}
/* @media screen and (max-width: 640px) {
  #app  {
    margin: 12px 0;
  }
}
@media screen and (min-width: 641px) and (max-width: 1440px) {
  #app  {
    margin: 12px 5%;
  }
}
@media screen and (min-width: 1441px) and (max-width: 2560px) {
  #app  {
    margin: 12px 10%;
  }
}
@media screen and (min-width: 2561px) {
  #app  {
    margin: 12px 15%;
  }
} */
body {
  background: #ffffff;
 
  margin: 0;
  /* padding: 0;  */
}
</style>
