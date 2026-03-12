<script setup>
import AboutUs from '@/components/AboutUs.vue';
import Gallery from '@/components/Gallery.vue';
import Reserve from '@/components/Reserve.vue';
import Services from '@/components/Services.vue';
</script>

<template>
  <main class="fundo_dark">
    <ul class="nav border-bottom border-2">
      <li class="nav-item">
        <a class="nav-link active" aria-current="page" href="#">INÍCIO</a>
      </li>
      <li class="nav-item">
        <a class="nav-link active" href="#">SOBRE</a>
      </li>
      <li class="nav-item">
        <a class="nav-link active" href="#">SERVIÇOS</a>
      </li>
      <li class="nav-item">
        <a class="nav-link active" href="#">GALERIA</a>
      </li>
      <li class="nav-item align-self-center ms-lg-auto p-2">
        <button class="button_gold">RESERVAR HORÁRIO</button>
      </li>
    </ul>
    <img src="/src/assets/logo.png" class="position-absolute top-0 start-50 translate-middle-x" width="200px">
    <Reserve />
    <AboutUs />
    <Services />
    <Gallery />
  </main>
</template>