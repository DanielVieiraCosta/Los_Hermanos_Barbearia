<script setup>
</script>

<template>
  <main>
    <div class="container pt-4 pb-4" id="servicos">
      <p>NOSSOS SERVIÇOS</p>
      <h2>O que oferecemos</h2>
      <div class="row gap-4">
        <div class="col-12 col-md-3 border card_services">
          <h4><img src="/src/assets/icons/tesoura.png" width="35px"> Corte De Cabelo</h4>
          <p>Corte moderno ou clássico, feito com técnica e atenção aos detalhes para valorizar seu estilo e formato de rosto.</p>
        </div>
        <div class="col-12 col-md-3 border card_services">
          <h4><img src="/src/assets/icons/navalha.png" width="30px"> Barba</h4>
          <p>Modelagem e acabamento da barba com máquina e navalha, garantindo um visual alinhado e bem cuidado.</p>
        </div>
        <div class="col-12 col-md-3 border card_services">
          <h4><img src="/src/assets/icons/barbearia.png" width="30px"> Corte + Barba</h4>
          <p>Experiência completa de grooming: corte de cabelo e modelagem de barba para um visual totalmente renovado.</p>
        </div>
        <div class="col-12 col-md-3 border card_services collapse" id="collapseService">
          <h4><img src="/src/assets/icons/alisador-de-cabelo.png" width="30px"> Progressiva</h4>
          <p>Tratamento capilar que reduz o volume e alinha os fios, deixando o cabelo mais liso, macio e fácil de cuidar.</p>
        </div>
        <div class="col-12 col-md-3 border card_services collapse" id="collapseService">
          <h4><img src="/src/assets/icons/sobrancelha.png" width="30px"> Sobrancelha</h4>
          <p>Ajuste e alinhamento das sobrancelhas para manter um visual natural e harmonioso.</p>
        </div>
      </div>
      <button class="button_gold mt-4" data-bs-toggle="collapse" data-bs-target="#collapseService">VER TODOS OS SERVIÇOS</button>
    </div>
  </main>
</template>