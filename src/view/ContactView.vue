<template>
    <div id="contact" class="relative w-full h-[50vh] sm:h-[60vh] md:h-[60vh] lg:h-[70vh] xl:h-[70vh] 2xl:h-[80vh] overflow-hidden">
      <!-- Container para a imagem que cobre toda a área -->
      <div class="absolute inset-0">
        <img src="../../public/image/img-1.webp" alt="imagem ilustrativa" class="w-full h-full object-cover">
      </div>
      <!-- Conteúdo sobre a imagem -->
      <div class="absolute inset-0 flex flex-col justify-center items-start p-5 md:p-10">
        <!-- Título principal -->
        <div class="text-left mb-6 md:mb-10 max-w-5xl">
          <h2 class="text-3xl sm:text-4xl md:text-5xl lg:text-6xl xl:text-7xl font-bold text-white leading-tight">
            Entre em contato
          </h2>
        </div>
      </div>
      <!-- Contato e informações no rodapé à esquerda -->
      <div class="absolute bottom-0 left-0 p-5 md:p-10 flex space-x-8">
        <!-- Endereço -->
        <div class="text-left text-white">
          <p class="text-sm sm:text-base md:text-lg lg:text-xl font-semibold leading-snug">
            Av. Goiás, 62 <br>
            Jardim Goiás <br>
            Goiânia - GO
          </p>
        </div>
        <!-- Informações de contato -->
        <div class="text-left text-white">
          <p class="text-sm sm:text-base md:text-lg lg:text-xl font-semibold leading-snug">
            Tel.(62) 3333-3333 <br>
            Email: i@gabi.com <br>
            Redes: @igabi
          </p>
        </div>
      </div>
    </div>
  </template>
  
  <style scoped>
  /* Opcional: Se precisar de ajuste adicional */
  </style>
  