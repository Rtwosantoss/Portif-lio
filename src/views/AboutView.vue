<script setup>
import RotasComponents from '../components/RotasComponents.vue';

</script>

<template>
  <div class="flex items-center justify-center min-h-screen px-6 space-x-10">
    <img class=" w-80 h-auto rounded-xl shadow-lg shadow-indigo-500/50" src="../assets/WhatsApp Image 2025-05-25 at 14.27.29.jpeg" alt="">
    
    <div class="max-w-xl text-left text-white">
      <div class="text-center">
      <h2 class="font-bold titulo-portifolio">Sobre mim:</h2>
      <br>
      <h2 class="font-bold text-left">Trajetoria:</h2>
      <br>

        <div class="text-left">
          <p >Meu nome é Rafael, tenho 21 anos e sou natural de Marília, interior de São Paulo. Minha trajetória começou no mundo do futebol, onde atuei como atleta por vários anos, desenvolvendo disciplina, resiliência e trabalho em equipe. Hoje, trago essa mesma mentalidade competitiva e dedicada para a área de tecnologia</p>
        </div>
        <br>

        <h2 class="font-bold text-left">Hard Skills:</h2>
        <br>  
        <div class="text-left">
          <p>Tenho conhecimentos básicos em HTML, CSS, Javascript, PHP, Laravel, C#, .NET e SQL, e estou sempre buscando aprimorar minhas habilidades através de cursos, projetos pessoais e desafios práticos.</p>
        </div>
        <br>
        <h2 class="font-bold text-left">Soft Skills:</h2>
        <br>
        <div class="text-left">
          <ul class="list-disc pl-5">
            <li>Proatividade</li>
            <li>Aprendizado contínuo</li>
            <li>Adaptabilidade</li>
          </ul>
        </div>
      <RotasComponents/>
      </div>
    </div> 
  </div>

</template>