<script setup>

</script>

<template>
 <div id="carouselExampleControlsNoTouching" class="carousel slide" data-bs-touch="false">
    <div class="carousel-indicators">
    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>
    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3"></button>
    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="3" aria-label="Slide 4"></button>
    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="4" aria-label="Slide 5"></button>
  </div>
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="https://missgolden.es/wp-content/uploads/2018/05/billie-eilish-white-hair.jpg" class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="https://okdiario.com/img/2019/07/12/cantantes-que-van-a-triunfar-655x368.jpg" class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="https://i.pinimg.com/originals/a4/e7/fc/a4e7fcaafb5531df903414adeb0049a8.jpg" class="d-block w-100" alt="...">
    </div>

    <div class="carousel-item">
      <img src="https://fotos.perfil.com/2018/11/04/trim/1140/641/con-tan-solo-21-anos-paulo-londra-el-cantante-de-trap-oriundo-de-cordoba-es-el-artista-de-estas-pampas-mas-reproducido-en-spotify-378917.jpg" class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="https://s.yimg.com/ny/api/res/1.2/kYzabX2MQW1GnlRcN3bXTQ--/YXBwaWQ9aGlnaGxhbmRlcjt3PTY0MDtoPTQyNw--/https://o.aolcdn.com/images/dims?crop=3522%2C2348%2C0%2C0&quality=85&format=jpg&resize=1600%2C1067&image_uri=https%3A%2F%2Fs.yimg.com%2Fos%2Fcreatr-images%2F2020-01%2F5b4004a0-4151-11ea-b5db-c66e227db589&client=a1acac3e1b3290917d92&signature=51e95f444a16ea752164ca41acb738baaac67f11" class="d-block w-100" alt="...">
    </div>

  </div>
  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleControlsNoTouching" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleControlsNoTouching" data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div>

</template>
<style scoped>
img{
  width: 100%;
  height: 260px;
}
@media screen and (min-width:400px) {
  #carouselExampleControlsNoTouching{
 display: none;
}

}
</style>