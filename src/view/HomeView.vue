<template>
    <div id="home" class="relative w-full h-[70vh] sm:h-[70vh] md:h-[70vh] lg:h-[70vh] xl:h-[80vh] 2xl:h-[90vh] overflow-hidden">
        <!-- Container para a imagem que cobre toda a área -->
        <div class="absolute inset-0">
            <img src="../../public/image/img-0.webp" alt="imagem ilustrativa" class="w-full h-full object-cover">
        </div>
        <!-- Conteúdo sobre a imagem -->
        <div class="absolute inset-x-0 top-1/2 transform -translate-y-1/2 text-center">
            <div class="mx-auto bg-transparent">
                <h3 class="text-3xl sm:text-5xl md:text-5xl lg:text-7xl xl:text-7xl font-bold text-white mb-2">
                    Perca peso e ganhe <br> confiança com <br> Gabriela Martins.
                </h3>
                <button class="uppercase font-bold mt-5 border-2 border-black bg-[#D8F2A5] hover:bg-[#FCAFE9] p-2 rounded-xl">
                    vamos começar
                </button>
            </div>
        </div>
    </div> 
</template>

<style scoped>
  /* Estilo Tailwind para centralizar conteúdo */
  .absolute {
    @apply flex items-center justify-center;
  }
</style>
