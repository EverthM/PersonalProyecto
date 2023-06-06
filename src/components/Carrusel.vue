<script setup>

</script>

<template>
  <div id="carouselExampleIndicators" class="carousel slide">
  <div class="carousel-indicators">
    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>
    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3"></button>
    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="3" aria-label="Slide 4"></button>
    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="4" aria-label="Slide 5"></button>


  </div>
  <div id="carru" class="carousel-inner">
    <div class="carousel-item active">
      <img id="uno" src="https://image.europafm.com/clipping/cmsimages02/2022/08/20/E8852051-DEEA-49A4-8BD6-482BABA03484/video-nicki-nicole-revela-posible-pista-que-esconde-mensaje-ibai-llanos_98.jpg?crop=2956,1663,x0,y0&width=1900&height=1069&optimize=low&format=webply" class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img id="dos" src="https://estaticos-cdn.elperiodico.com/clip/dfa3c9b9-faca-4b41-b52b-e72d8bbdd584_alta-libre-aspect-ratio_default_0.jpg" class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img id="tres" src="https://tn.com.ar/resizer/xAnwjzqzgKtDVmGY2OnuXA3aXGE=/767x0/smart/filters:format(webp)/cloudfront-us-east-1.images.arcpublishing.com/artear/BLEYNCAGXFGUD74DLODV2XHCRU.jpg" class="d-block w-100" alt="...">
    </div>

    <div class="carousel-item">
      <img id="dos" src="https://www.billboard.com/wp-content/uploads/2023/02/karol-g-2023-cr-Pablo-Escudero-billboard-1548.jpg?w=942&h=623&crop=1" class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img id="tres" src="https://imagenes.elpais.com/resizer/Lzw9nPOgcRjMUdhXL0HL9-qzLTA=/1960x1103/cloudfront-eu-central-1.images.arcpublishing.com/prisa/TV22SJWVXKNIHD4EFA66URSNKM.jpg" class="d-block w-100" alt="...">
    </div>





  </div>
  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
  
</div>

</template>
<style scoped>
#uno,#dos,#tres{
  width: 100%;
  height: 260px;
}
@media screen and (min-width:400px) {
  #carouselExampleIndicators{
 display: none;
}

}



</style>