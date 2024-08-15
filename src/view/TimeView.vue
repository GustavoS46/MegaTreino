<template>
    <div id="time" class="relative bg-[#F4F4F2] py-10 min-h-[40vh] flex items-center">
        <div class="max-w-screen-xl mx-auto px-4 w-full">
            <!-- Título com fundo vermelho, centralizado -->
            <div class="text-center mb-8">
                <h2 class="text-4xl font-sans font-semibold uppercase">Nossos serviços</h2>
            </div>

            <!-- Grid de serviços -->
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Coluna 1 -->
                <div class="overflow-hidden">
                    <img src="../../public/image/img-3.webp" alt="treino matinal" class="w-full h-86 object-cover">
                    <div class="p-4">
                        <h3 class="text-xl font-semibold mb-2 text-left uppercase">Treino Matinal</h3>
                        <p class="text-left">8h - 9h</p>
                        <div class="border-t-2 border-black w-[100%] mt-2 mb-4"></div>
                        <button class="uppercase font-bold mt-2 w-full border-2 border-black bg-[#ACB1FB] hover:bg-[#D8F2A5] p-2 rounded-xl">
                            Agendar
                        </button>
                    </div>
                </div>

                <!-- Coluna 2 -->
                <div class="overflow-hidden">
                    <img src="../../public/image/img-6.webp" alt="power jam" class="w-full h-86 object-cover">
                    <div class="p-4">
                        <h3 class="text-xl font-semibold mb-2 text-left uppercase">Power Jam</h3>
                        <p class="text-left">10h - 11h</p>
                        <div class="border-t-2 border-black w-[100%] mt-2 mb-4"></div>
                        <button class="uppercase font-bold mt-2 w-full border-2 border-black bg-[#FBA163] hover:bg-[#D8F2A5] p-2 rounded-xl">
                            Agendar
                        </button>
                    </div>
                </div>

                <!-- Coluna 3 -->
                <div class="overflow-hidden">
                    <img src="../../public/image/img-5.webp" alt="groove jam" class="w-full h-86 object-cover">
                    <div class="p-4">
                        <h3 class="text-xl font-semibold mb-2 text-left uppercase">Groove Jam</h3>
                        <p class="text-left">18h - 19h</p>
                        <div class="border-t-2 border-black w-[100%] mt-2 mb-4"></div>
                        <button class="uppercase font-bold mt-2 w-full border-2 border-black bg-[#FCAFE9] hover:bg-[#D8F2A5] p-2 rounded-xl">
                            Agendar
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
/* Opcional: Se precisar de ajuste adicional */
</style>
