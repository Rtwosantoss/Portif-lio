<script setup>
import RotasComponents from '../components/RotasComponents.vue';

</script>

<template>
    <h1 class="titulo-portifolio text-white text-center mt-20 text-4xl">Portifólio</h1>
         
<div class="py-20 flex min-h-screen flex-col items-center text-white"> 

    <div class="flex items-center justify-center px-6 space-x-10 text-left max-w-6xl mb-12 mr-80">
        <img class="w-[500px] h-auto rounded-xl shadow-lg shadow-indigo-500/50" src="../assets/Captura de tela 2025-05-27 131710.png" alt="">
        <p>Tela para fãs de YU-GI-OH onde mostra as cartas na tela. Para a exibição das cartas foi usada uma API. A linguagem utilizada para consumo e estruturação foi Javascript, além de HTML e CSS para estilização.</p>
    </div>

    <div class="flex items-center justify-center px-6 space-x-10 text-left max-w-6xl ml-80">
        <p>Tela de login de SEGA feita a partir de princípios básicos como HTML e CSS sem nenhum tipo de uso de Javascript ou outra linguagem de programação</p>
        <img class="w-[500px] h-auto rounded-xl shadow-lg shadow-indigo-500/50" src="../assets/Captura de tela 2025-05-27 131333.png" alt="">
    </div>

    <div class="py-20">
        <RotasComponents/>
    </div>

</div>
   
    
</template>