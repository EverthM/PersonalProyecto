<script setup>


</script>

<template>
  <header class="principal">

  <div class="Letras">
<h1 class="Music">Music</h1>

  </div>

<div class="Doscontent">
  <div class="lupa">
    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
  <path stroke-linecap="round" stroke-linejoin="round" d="M15.75 15.75l-2.489-2.489m0 0a3.375 3.375 0 10-4.773-4.773 3.375 3.375 0 004.774 4.774zM21 12a9 9 0 11-18 0 9 9 0 0118 0z" />
</svg>

  </div>
<div class="mas">
  <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
  <path stroke-linecap="round" stroke-linejoin="round" d="M12 9v6m3-3H9m12 0a9 9 0 11-18 0 9 9 0 0118 0z" />
</svg>

</div>

</div>

</header>


</template>

<style scoped>

.principal{
width: 100%;
height: 50px;
display: flex;
  align-items: center;
  justify-content: space-between;
  background-color: black;
  
}
.Doscontent{
  height: 10%;
  width: 30%;
  display: flex;
  align-items: center;
  justify-content: space-between;
  
  
}


.Music{
font-family: 'Times New Roman', Times, serif;
font-weight: bold;
font-size: 220%;
padding: 10px;
color: white
;

}
.Music:hover{
  color: magenta;
    
  }
.Letras{
  height: 10%;
  width: 10%;
  display: flex;
  align-items: center;
  
}

svg{
  height: 100%;
  height: 100%;
}
.lupa,.mas{
  height: 50px;
  width: 50px;
  color: white;
}
.lupa:hover{
  color: magenta;
}
.mas:hover{
  color: magenta;
}

@media screen and (max-width:500px) {
    .principal{
      width: 100%;
        display: flex;
        gap: 100px;
        background-color:darkmagenta;
    }

  .Doscontent{
  height: 40%;
  width: 40%;
  display: flex;
  align-items: center;
  justify-content: space-between;
  

}
.Music{
font-family: 'Times New Roman', Times, serif;
font-weight: bold;
font-size: 220%;
padding: 10px;
color: darkcyan;

}
.lupa,.mas{
  height: 50px;
  width: 50px;
  color: darkcyan;
}
   
}

</style>
