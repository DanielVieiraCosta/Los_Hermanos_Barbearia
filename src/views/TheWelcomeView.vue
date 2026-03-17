<script setup>
import AboutUs from '@/components/AboutUs.vue';
import Footer from '@/components/Footer.vue';
import Gallery from '@/components/Gallery.vue';
import Reserve from '@/components/Reserve.vue';
import Services from '@/components/Services.vue';
</script>

<template>
  <header class="fundo_dark sticky-top">
    <ul class="nav border-bottom border-2">
      <li class="nav-item">
        <a class="nav-link active" aria-current="page" href="#">INÍCIO</a>
      </li>
      <li class="nav-item">
        <a class="nav-link active" href="#sobre">SOBRE</a>
      </li>
      <li class="nav-item">
        <a class="nav-link active" href="#servicos">SERVIÇOS</a>
      </li>
      <li class="nav-item">
        <a class="nav-link active" href="#galeria">GALERIA</a>
      </li>
      <li class="nav-item align-self-center ms-lg-auto p-2">
        <a href="https://w.app/barbearialoshermanos" target="_blank"><button class="button_gold">RESERVAR HORÁRIO</button></a>
      </li>
    </ul>
    <img src="/src/assets/logo.png" class="position-absolute top-0 start-50 translate-middle-x" width="180px">
  </header>
  <main class="fundo_dark">
    <Reserve />
    <AboutUs />
    <Services />
    <Gallery />
  </main>
  
  <footer class="fundo_dark">
    <Footer />
  </footer>
</template>