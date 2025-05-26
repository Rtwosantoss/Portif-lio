<script setup>
import Navbar from './components/NavbarComponent.vue';
import Whatsapp from './components/WhatsappComponent.vue';
import Footer from './components/FooterComponent.vue'

</script>

<template>
<div class="flex flex-col min-h-screen">
  <Navbar/>
  <main class="flex-grow bg-gray-900">  
    <router-view></router-view>
    <Whatsapp/>
  </main>
  <Footer/>
</div>
</template>

