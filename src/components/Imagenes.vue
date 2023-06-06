<script setup>

</script>
<template>
<div class="Principal">
  
<div class="Titulo">

<div class="picos"> 
    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
  <path stroke-linecap="round" stroke-linejoin="round" d="M15.75 19.5L8.25 12l7.5-7.5" />
</svg>
<svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
  <path stroke-linecap="round" stroke-linejoin="round" d="M8.25 4.5l7.5 7.5-7.5 7.5" />
</svg>

</div>
<div class="mejor">
<h1>Mejora tu cuenta</h1>
</div>
<div class="instalar">
    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
  <path stroke-linecap="round" stroke-linejoin="round" d="M3 16.5v2.25A2.25 2.25 0 005.25 21h13.5A2.25 2.25 0 0021 18.75V16.5M16.5 12L12 16.5m0 0L7.5 12m4.5 4.5V3" />
</svg>
<h1>Instalar App</h1>
</div>
<div class="user">
    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
  <path stroke-linecap="round" stroke-linejoin="round" d="M17.982 18.725A7.488 7.488 0 0012 15.75a7.488 7.488 0 00-5.982 2.975m11.963 0a9 9 0 10-11.963 0m11.963 0A8.966 8.966 0 0112 21a8.966 8.966 0 01-5.982-2.275M15 9.75a3 3 0 11-6 0 3 3 0 016 0z" />
</svg>

</div>

</div>

<div class="Estaciones">
    
        <h1>Estaciones Populares</h1>
</div>

    <div class="bloc1">
        <div class="uno">
            <img id="uno" src="https://image.europafm.com/clipping/cmsimages02/2022/08/20/E8852051-DEEA-49A4-8BD6-482BABA03484/video-nicki-nicole-revela-posible-pista-que-esconde-mensaje-ibai-llanos_98.jpg?crop=2956,1663,x0,y0&width=1900&height=1069&optimize=low&format=webply" alt="">
        </div>
        <div class="dos">
            <img id="dos" src="https://estaticos-cdn.elperiodico.com/clip/dfa3c9b9-faca-4b41-b52b-e72d8bbdd584_alta-libre-aspect-ratio_default_0.jpg" alt="">
        </div>
        <div class="tres">
            <img id="tres" src="https://tn.com.ar/resizer/xAnwjzqzgKtDVmGY2OnuXA3aXGE=/767x0/smart/filters:format(webp)/cloudfront-us-east-1.images.arcpublishing.com/artear/BLEYNCAGXFGUD74DLODV2XHCRU.jpg" alt="">
        </div>
        <div class="cuatro">
            <img id="dos" src="https://www.billboard.com/wp-content/uploads/2023/02/karol-g-2023-cr-Pablo-Escudero-billboard-1548.jpg?w=942&h=623&crop=1" alt="">
        </div>
        <div class="cinco">
            <img id="tres" src="https://imagenes.elpais.com/resizer/Lzw9nPOgcRjMUdhXL0HL9-qzLTA=/1960x1103/cloudfront-eu-central-1.images.arcpublishing.com/prisa/TV22SJWVXKNIHD4EFA66URSNKM.jpg" alt="">
        </div>

        
    
    </div>
    <div class="Estaciones">
    
    <h1>Tus Playlist Favoritas</h1>
</div>

    <div class="bloc2">
        <div class="seis">
            <img src="https://missgolden.es/wp-content/uploads/2018/05/billie-eilish-white-hair.jpg"  alt="">
        </div>
        <div class="siete">
            <img src="https://okdiario.com/img/2019/07/12/cantantes-que-van-a-triunfar-655x368.jpg"  alt="">
        </div>
        <div class="ocho">
            <img src="https://i.pinimg.com/originals/a4/e7/fc/a4e7fcaafb5531df903414adeb0049a8.jpg"  alt="">
        </div>
        <div class="nueve">
            <img src="https://fotos.perfil.com/2018/11/04/trim/1140/641/con-tan-solo-21-anos-paulo-londra-el-cantante-de-trap-oriundo-de-cordoba-es-el-artista-de-estas-pampas-mas-reproducido-en-spotify-378917.jpg" alt="">
        </div>
        <div class="dies">
            <img src="https://s.yimg.com/ny/api/res/1.2/kYzabX2MQW1GnlRcN3bXTQ--/YXBwaWQ9aGlnaGxhbmRlcjt3PTY0MDtoPTQyNw--/https://o.aolcdn.com/images/dims?crop=3522%2C2348%2C0%2C0&quality=85&format=jpg&resize=1600%2C1067&image_uri=https%3A%2F%2Fs.yimg.com%2Fos%2Fcreatr-images%2F2020-01%2F5b4004a0-4151-11ea-b5db-c66e227db589&client=a1acac3e1b3290917d92&signature=51e95f444a16ea752164ca41acb738baaac67f11" alt="">
        </div>
        

    </div>

</div>

</template>


<style>

*{
  margin: 0;
}
@media screen and (max-width:500px) {
.Principal{
    display: none;
}
}

@media screen and (min-width:500px) {
img{
width: 100%;
height: 100%;
}

img:hover{
transform: scale(1.15);

}
.bloc1{
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.uno,.dos,.tres,.cuatro,.cinco{
    width: 250px;
    height: 250px;
}

.bloc2{
    display: flex;
    align-items: center;
    justify-content: space-between;
}
.seis,.siete,.ocho,.nueve,.dies{
    width: 250px;
    height: 250px;
}

svg{
    width: 40px;
    height: 40px;
}
.picos,.instalar,.user,.mejor{
    display:flex;
   
    
}
.mejor,.instalar{
    border: 2px solid white;
    border-radius: 20px;
    width: 200px;
    height: 50px;
    display: flex;
    align-items: center;
    justify-content: center;
}
.Titulo{
    width: 100%;
    height: 100px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    background-color: black;
    color: white;
    
}
h1{
    font-size: 150%;
}
.Estaciones{
    width: 100%;
    height: 50px;
    color: white;
    background-color: black;
    display: flex;
    align-items: center;
    padding: 10px;
    
}

}

</Style>