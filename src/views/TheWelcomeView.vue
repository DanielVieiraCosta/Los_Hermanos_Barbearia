<script setup>
import AboutUs from '@/components/AboutUs.vue';
import Footer from '@/components/Footer.vue';
import Gallery from '@/components/Gallery.vue';
import Reserve from '@/components/Reserve.vue';
import Services from '@/components/Services.vue';
</script>

<template>
  <nav class="fundo_dark navbar sticky-top navbar-expand-lg border-bottom border-2">
    <div class="container-fluid">
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#barra_nav" aria-controls="navbarTogglerDemo03" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="barra_nav">
        <ul class="navbar-nav w-100">
          <li class="nav-item">
            <a class="nav-link" aria-current="page" href="#">INÍCIO</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#sobre">SOBRE</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#servicos">SERVIÇOS</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#galeria">GALERIA</a>
          </li>
          <li class="nav-item ms-lg-auto pt-1 pe-4">
            <a href="https://w.app/barbearialoshermanos" target="_blank"><button class="button_gold">RESERVAR HORÁRIO</button></a>
          </li>
        </ul>
      </div>
      <img src="/src/assets/logo.png" class="d-none d-md-block position-absolute top-0 start-50 translate-middle-x" width="180px">
    </div>
  </nav>
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