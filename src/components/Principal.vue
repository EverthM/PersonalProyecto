<script setup>

  import my_Header from './Header.vue'
  import my_Banner from './Banner.vue'
  import my_Menu from './Menu.vue'
  import my_Carrusel from './Carrusel.vue';
  import Inicio from './Inicio.vue';
  import Playlist from './Playlist.vue'
  import Carrusel2 from './Carrusel2.vue';
  import Final from './Final.vue'
  import Footer from './Footer.vue'
  import Imagenes from './Imagenes.vue'

</script>

<template>
  
<div class="main-container">

  <div class="bloque1">
  <Inicio></Inicio>
  <my_Header class="header"></my_Header>
  <Playlist></Playlist>
</div>

<div class="bloque2">
<my_Banner class="banner"></my_Banner>
<my_Menu class="menu"></my_Menu>
<my_Carrusel class="carrusel"></my_Carrusel>
<Carrusel2></Carrusel2>
<Imagenes></Imagenes>

</div>

</div>

<Footer></Footer>
<Final></Final>
</template>

<style scoped>
*{
  margin: 0;
}
@media screen and (min-width:400px) {

  .main-container{
    display: flex;
    gap: 2px;
  }
.bloque1{
  width: 30%;
  height: 100%;
  background-color: black;
  
}
.bloque2{
  width: 100%;
  height: 100%;
  background-color: black;
  
}

}
</style>