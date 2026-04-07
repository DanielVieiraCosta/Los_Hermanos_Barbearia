<script></script>

<template>
  <div class="modal fade" id="modal_reserva" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
    <div class="modal-dialog modal-lg">
      <div class="modal-content modal_reserve">
        <div class="modal-header">
          <h1 class="modal-title fs-5" id="exampleModalLabel">Faça a sua reserva!!</h1>
          <button type="button" class="btn_close ms-auto" data-bs-dismiss="modal" aria-label="Close"><i class="bi bi-x-lg"></i></button>
        </div>
        <div class="modal-body d-flex justify-content-around gap-2 barbearias">
          <div class="card card_dark" type="button" style="width: 19rem;">
            <a href="http://wa.me/5514991263898" target="_blank" class="font_secundaria link-underline link-underline-opacity-0">
              <img src="/src/assets/barbearia_1.jpeg" class="card-img-top">
              <div class="card-body d-grid">
                <h4>Barbearia Los Hermanos</h4>
                <h4>Unidade 1</h4>
                <div class="d-none d-lg-block">
                  <h6>Segunda a sexta das 9h30 às 18h30</h6>
                  <h6>Sábado das 9h às 15h</h6>
                  <h6>R. São Luiz, 1589 - Centro</h6>
                </div>
              </div>
            </a>
          </div>
          <div class="card card_dark" style="width: 19rem;">
            <a href="https://wa.me/5514996850688" target="_blank" class="font_secundaria link-underline link-underline-opacity-0">
              <img src="/src/assets/barbearia_2.jpeg" type="button" class="card-img-top">
              <div class="card-body d-grid">
                <h4>Barbearia Los Hermanos</h4>
                <h4>Unidade 2</h4>
                <div class="d-none d-lg-block">
                  <h6>Segunda a sexta das 9h30 às 18h30</h6>
                  <h6>Sábado das 9h às 15h</h6>
                  <h6>R. Ten. Antônio João, 215 - Altaneira</h6>
                </div>
              </div>
            </a>
          </div>
        </div>
        <div class="modal-footer">
          <button type="button" class="btn btn-danger" data-bs-dismiss="modal">Voltar</button>
        </div>
      </div>
    </div>
  </div>
</template>