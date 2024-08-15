<template>
    <div class="fixed top-0 left-0 w-full bg-[#FA92C2] px-5 py-5 z-50">
        <div class="flex items-center justify-between max-w-screen-2xl mx-auto">
            <!-- Logo e Títulos à Esquerda -->
            <div class="flex items-center">
                <img src="../../public/image/letra-g.svg" alt="logo" class="w-[68px] h-auto">
                <!-- Container para os dois títulos -->
                <div class="flex flex-col ml-3" v-if="!isMenuOpen">
                    <h1 class="font-noto-sans text-xl font-bold text-white uppercase mt-0">
                        MegaTreino <br> com Gabi
                    </h1>
                </div>
            </div>

            <div class="flex items-center ml-auto">
                <button 
                    @click="toggleMenu"
                    class="lg:hidden text-white text-2xl relative focus:outline-none"
                >
                    <span :class="{'hidden': isMenuOpen, 'block': !isMenuOpen}" class="block">☰</span>
                    <span :class="{'block': isMenuOpen, 'hidden': !isMenuOpen}" class="block text-2xl">✕</span>
                </button>
            </div>
            
            <!-- Menu à Direita -->
            <nav :class="{'block': isMenuOpen, 'hidden': !isMenuOpen}"
                class="absolute right-0 top-full bg-[#FA92C2] w-full lg:static lg:w-auto lg:flex lg:space-x-4 text-xl lg:text-right lg:text-[#815BC4] text-white">
                <a href="#home" class="block lg:inline p-4 lg:p-0 text-[#815BC4]">Home</a>
                <a href="#about" class="block lg:inline p-4 lg:p-0 text-white hover:text-[#815BC4]">Quem Sou</a>
                <a href="#time" class="block lg:inline p-4 lg:p-0 text-white hover:text-[#815BC4]">Horários</a>
                <a href="#training" class="block lg:inline p-4 lg:p-0 text-white hover:text-[#815BC4]">Treinos</a>
                <a href="#health" class="block lg:inline p-4 lg:p-0 text-white hover:text-[#815BC4]">Saúde</a>
                <a href="#testimonials" class="block lg:inline p-4 lg:p-0 text-white hover:text-[#815BC4]">Depoimentos</a>
                <a href="#contact" class="block lg:inline p-4 lg:p-0 text-white hover:text-[#815BC4]">Contato</a>
            </nav>
        </div>
    </div>
</template>

<script>
export default {
  data() {
    return {
      isMenuOpen: false
    };
  },
  methods: {
    toggleMenu() {
      this.isMenuOpen = !this.isMenuOpen;
    }
  }
};
</script>

<style scoped>
/* Estilos adicionais, se necessário */
</style>
