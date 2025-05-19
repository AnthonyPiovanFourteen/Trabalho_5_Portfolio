<script setup>
import '../assets/css/card.css';
</script>

<template>
  <div class="min-h-screen flex justify-center items-start pt-16 bg-white px-4">
    <div
      class="max-w-5xl w-full flex flex-col items-center gap-10 p-6 border border-gray-300 rounded-lg shadow-md"
    >
      <div class="flex-1">
        <h1 class="text-3xl font-bold mb-4">Sobre mim 📄</h1>
        <p class="text-gray-700 mb-2">
          Olá! Eu sou <strong>Anthony</strong>, tenho dezenove anos e estou no terceiro
          período da faculdade de Análise e Desenvolvimento de Sistemas. Desde
          2021, venho construindo minha base em programação, começando com
          Python, C++ para Arduino e HTML, explorando diversas linguagens ao
          longo do curso.
        </p>
        <p class="text-gray-700 mb-2">
          Trabalho no setor de logística administrativa desde 2024 e também curso
          Logística e Gestão de Suprimentos, o que me proporciona uma visão ampla
          sobre organização e gestão de processos.
        </p>
        <p class="text-gray-700 mb-2">
          Sou comunicativo e consigo expressar minhas ideias com clareza, além de ser
          dedicado à resolução eficaz de problemas. Tenho facilidade para me
          adaptar a ambientes dinâmicos e sou comprometido com o cumprimento de
          prazos.
        </p>
        <p class="text-gray-700 mb-2">
          Ainda não atuo oficialmente na área de desenvolvimento, mas possuo grande
          interesse em banco de dados e busco constantemente aprimorar minhas
          habilidades para crescer profissionalmente.
        </p>
        <p class="text-gray-700">
          Fora do mundo da tecnologia, sou apaixonado por cinema — meu filme favorito
          é <em>Malcolm X</em>, dirigido por Spike Lee. Gosto de explorar narrativas
          e histórias inspiradoras, que também alimentam minha criatividade e
          visão.
        </p>
        <br />
        <h1 class="text-3xl font-bold mb-4">Linguagens preferidas 🖥️</h1>
        <div class="flex justify-center items-center gap-6 mt-8 flex-wrap">
          <div class="perspective w-64 h-64">
            <div class="relative w-full h-full transition-transform duration-700 transform-style preserve-3d hover:rotate-y-180 cursor-pointer">
              <div class="absolute w-full h-full backface-hidden rounded-lg overflow-hidden shadow-lg">
                <img src="../assets/images/python.png" alt="Python" class="w-full h-full object-cover"/>
                <h4 class="absolute bottom-2 w-full text-center text-white text-sm bg-black bg-opacity-50">
                  Python
                </h4>
              </div>

              <div class="absolute w-full h-full rotate-y-180 backface-hidden bg-gradient-to-br from-green-600 to-green-800 text-white rounded-lg shadow-lg flex flex-col justify-center items-center p-4 text-center">
                <h2 class="text-xl font-bold mb-2">Python</h2>
                <p class="text-sm italic mb-4">
                  Linguagem versátil e poderosa para automação, ciência de dados e muito mais.
                </p>
                <p class="text-xs font-semibold">
                  Minha principal linguagem de estudo desde 2021.
                </p>
              </div>
            </div>
          </div>

          <div class="perspective w-64 h-64">
            <div class="relative w-full h-full transition-transform duration-700 transform-style preserve-3d hover:rotate-y-180 cursor-pointer">
              <div class="absolute w-full h-full backface-hidden rounded-lg overflow-hidden shadow-lg">
                <img src="../assets/images/c++.jpg" alt="C++" class="w-full h-full object-cover"/>
                <h4 class="absolute bottom-2 w-full text-center text-white text-sm bg-black bg-opacity-50">
                  C++
                </h4>
              </div>
              <div class="absolute w-full h-full rotate-y-180 backface-hidden bg-gradient-to-br from-blue-700 to-blue-900 text-white rounded-lg shadow-lg flex flex-col justify-center items-center p-4 text-center">
                <h2 class="text-xl font-bold mb-2">C++</h2>
                <p class="text-sm italic mb-4">
                  Usada para programação de hardware e sistemas embarcados, como Arduino.
                </p>
                <p class="text-xs font-semibold">
                  Estudo desde meus primeiros projetos em 2021.
                </p>
              </div>
            </div>
          </div>

          <div class="perspective w-64 h-64">
            <div class="relative w-full h-full transition-transform duration-700 transform-style preserve-3d hover:rotate-y-180 cursor-pointer">
              <div class="absolute w-full h-full backface-hidden rounded-lg overflow-hidden shadow-lg">
                <img src="../assets/images/sql.webp" alt="SQL" class="w-full h-full object-cover"/>
                <h4 class="absolute bottom-2 w-full text-center text-white text-sm bg-black bg-opacity-50">
                  SQL
                </h4>
              </div>
              <div class="absolute w-full h-full rotate-y-180 backface-hidden bg-gradient-to-br from-yellow-700 to-yellow-900 text-white rounded-lg shadow-lg flex flex-col justify-center items-center p-4 text-center">
                <h2 class="text-xl font-bold mb-2">SQL</h2>
                <p class="text-sm italic mb-4">
                  Linguagem essencial para gerenciamento e consulta de bancos de dados.
                </p>
                <p class="text-xs font-semibold">
                  Uma área que tenho grande interesse profissional.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
