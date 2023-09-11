<template>
    <nav ref="navbar" class="fixed top-0 left-0 w-full bg-primary-200 z-20 transition duration-200">
        <div class="container flex items-center justify-between h-20">
            <div class="relative z-30 flex items-center gap-2 mb-2 lg:mb-0">
                <h1 class="text-white font-bold text-lg lg:text-1xl">Rob<span class="text-secondary">Sage</span>me</h1>  
            </div>
            
            <div class="flex lg:hidden items-center gap-2">
                <button></button>
                <button></button>
            </div>

            <div class="absolute lg:static top-20 inset-x-0 flex flex-col lg:flex-row items-center gap-5 lg:gap-10 bg-primary-200 lg:bg-transparent pt-5 pb-10 px-5 lg:p-0 transition duration-500 lg:duration-200 lg:-translate-y-0" :class="!showMenu ? 'translate-y-[-150%]' : '-translate-y-0'"> 
                <a @click="showMenu = false" class="text-white font-medium" href="#home">Home</a>
                <a @click="showMenu = false" class="text-white font-medium" href="#home">Tech Stack</a>
                <a @click="showMenu = false" class="text-white font-medium" href="#home">Projects</a>
                <a @click="showMenu = false" class="text-white font-medium" href="#home">Work Experience</a>
                <button class="hidden md:block px-8 py-3 rounded-full text-white font-medium tracking-wider uppercase bg-secondary w-full lg:w-auto">Contact</button>
            </div>
        </div>
    </nav> 
</template>
<script setup>

</script>
<style scoped>

</style>