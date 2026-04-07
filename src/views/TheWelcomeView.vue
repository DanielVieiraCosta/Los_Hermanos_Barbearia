<script setup>
import AboutUs from '@/components/AboutUs.vue';
import Barber from '@/components/Barber.vue';
import Footer from '@/components/Footer.vue';
import Gallery from '@/components/Gallery.vue';
import Modal from '@/components/Modal.vue';
import Reserve from '@/components/Reserve.vue';
import Services from '@/components/Services.vue';
</script>

<template>
  <nav class="fundo_dark navbar navbar-dark sticky-top navbar-expand-lg border-bottom border-2">
    <div class="container-fluid">
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#barra_nav">
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
            <a class="nav-link" href="#profissionais">PROFISSIONAIS</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#galeria">GALERIA</a>
          </li>
          <li class="nav-item ms-lg-auto pt-1 pe-4">
            <button class="button_gold" data-bs-toggle="modal" data-bs-target="#modal_reserva">RESERVAR HORÁRIO</button>
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
    <Barber />
    <Gallery />
    <Modal />
  </main>
  
  <footer class="fundo_dark">
    <Footer />
  </footer>
</template>