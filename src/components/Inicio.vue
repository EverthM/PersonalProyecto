<script setup>

</script>

<template>
<div class="contenedor">
<div class="Inicio">
    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
  <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 12l8.954-8.955c.44-.439 1.152-.439 1.591 0L21.75 12M4.5 9.75v10.125c0 .621.504 1.125 1.125 1.125H9.75v-4.875c0-.621.504-1.125 1.125-1.125h2.25c.621 0 1.125.504 1.125 1.125V21h4.125c.621 0 1.125-.504 1.125-1.125V9.75M8.25 21h8.25" />
</svg>
<h1>Inicio</h1>
</div>
<div class="Buscar">
    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
  <path stroke-linecap="round" stroke-linejoin="round" d="M21 21l-5.197-5.197m0 0A7.5 7.5 0 105.196 5.196a7.5 7.5 0 0010.607 10.607zM10.5 7.5v6m3-3h-6" />
</svg>
<h1>Buscar</h1>
</div>

</div>

</template>

<style scoped>
@media screen and (max-width:400px) {
    .contenedor{
    display: none;
}
}
@media screen and (min-width:400px) {
.contenedor{
    background-color: black;
    width: 100%;
    height: 100px;
}
svg{
    width: 30px;
    height: 30px;
    color: white;
}
h1{
    color: white;
    font-size: 150%;
}
.Inicio,.Buscar{
    display: flex;
    gap: 10px;
}
}

</style>