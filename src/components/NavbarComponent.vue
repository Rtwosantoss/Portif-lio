<template>
    <body class="bg-white">
        <nav class="bg-gradient-to-r from-black via-purple-500 to-pink-500 text-white py-5 px-8 flex justify-between items-center">
            
        <h1 class="ml-72 font-bold text-4xl titulo-portifolio"><router-link to="/">Portifólio</router-link></h1>
        <ul class="flex gap-6">
            <li>
                <router-link to="/" class="hover:underline hover:text-pink-500 hover:bg-white py-1 px-3 top-1 rounded-tr-lg rounded-bl-lg">Início</router-link>
            </li>
            <li>
                <router-link to="/about" class="hover:underline hover:text-pink-500 hover:bg-white py-1 px-3 rounded-tr-lg rounded-bl-lg">Sobre</router-link>
            </li>
            <li>
                <router-link to="/portifolio" class="hover:underline hover:text-pink-500 hover:bg-white py-1 px-3 rounded-tr-lg rounded-bl-lg">Potifolio</router-link>
            </li>
            <li>
                <router-link to="/contact" class="hover:underline hover:text-pink-500 hover:bg-white py-1 px-3 rounded-tr-lg rounded-bl-lg">Contato</router-link>
            </li>
        </ul>
    </nav>
        
    </body>
    
</template>

<style>
    @import url('https://fonts.cdnfonts.com/css/ventera');

    .titulo-portifolio{
        font-family: 'Ventera', sans-serif;                                        
    }
</style>
                
