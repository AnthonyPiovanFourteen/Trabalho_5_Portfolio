<script setup>
import '../assets/css/card.css';
</script>
<template>
  <div class="min-h-screen flex justify-center items-start pt-16 bg-white px-4">
    <div class="max-w-8xl w-full flex flex-col md:flex-row items-center gap-10 p-6 border border-gray-300 rounded-lg shadow-md">
      <div class="w-64 h-64 perspective">
        <div class="relative w-full h-full transition-transform duration-700 transform-style preserve-3d hover:rotate-y-180">
          <div class="absolute w-full h-full backface-hidden">
            <img src="../assets/images/card-frente.jpg" alt="Frente" class="w-full h-full object-cover rounded-lg shadow-lg"/>
            <h4 class="absolute bottom-2 w-full text-center text-white text-sm">Veja o Card!!!</h4>
          </div>
          
          <div class="absolute w-full h-full rotate-y-180 backface-hidden bg-gradient-to-br from-blue-800 to-indigo-900 text-white rounded-lg shadow-lg flex flex-col justify-center items-center p-4 text-center">
            <h2 class="text-xl font-bold mb-2">Anthony Piovan</h2>
            <img src="../assets/images/bug.png" alt="bug" class="w-12 h-12 mx-auto mb-2">
            <h3 class="text-sm italic mb-4">O Domador de Bugs</h3>
            <p class="text-xs mb-2">Tem a habilidade de conversar com bugs...embora eles ainda não obedeçam.</p>
            <p class="text-xs font-semibold">Use esta carta apenas quando todos já perderam as esperanças.</p>
          </div>
        </div>
      </div>
      <div class="flex-1">
        <h1 class="text-3xl font-bold mb-4">Bem-vindo ao meu portfólio! ✌️</h1>
        <p class="text-gray-700 mb-2">
          Eu sou o <strong>Anthony</strong>, estudante de Análise e Desenvolvimento de Sistemas, natural de Marília e apaixonado por tecnologia.
        </p>
        <p class="text-gray-700 mb-2">
          Estou em busca da minha primeira oportunidade na área de desenvolvimento, sempre estudando e praticando!!
        </p>
        <p class="text-gray-700">
          Aqui você vai ver um pouco da minha trajetória e como me encontrar. Ainda estou começando, mas com muita vontade de crescer e aprender todos os dias!!
        </p>
      </div>
    </div>
  </div>
</template>
