<script></script>

<template>
  <main class="fundo_secundario">
    <div class="container pt-4 pb-4" id="profissionais">
      <p>PROFISSIONAIS</p>
      <h2>Conheça mais sobre nossos barbeiros <img src="/src/assets/icons/barbeiro.png" width="30px"></h2>
      <div class="row justify-content-around pt-4 gap-2">
        <div class="card card_dark" style="width: 15rem;">
          <a data-bs-toggle="modal" data-bs-target="#sobre_tinetti">
            <img src="/src/assets/barbeiros/img_tinetti.jpeg" class="card-img-top">
            <div class="card-body">
              <h6>Bruno Tinetti — Unidade Centro (Unidade 1)</h6>
            </div>
          </a>
        </div>
        <div class="card card_dark" style="width: 15rem;">
          <a data-bs-toggle="modal" data-bs-target="#sobre_rafael">
            <img src="/src/assets/barbeiros/img_rafael.jpeg" class="card-img-top">
            <div class="card-body">
              <h6>Rafael "Feijão" - Unidade Centro (Unidade 1)</h6>
            </div>
          </a>
        </div>
        <div id="collapseBarber" class="card card_dark collapse d-md-block" style="width: 15rem;">
          <a data-bs-toggle="modal" data-bs-target="#sobre_gabriel">
            <img src="/src/assets/barbeiros/img_gabriel.jpeg" class="card-img-top">
            <div class="card-body">
              <h6>Gabriel - Unidade 2</h6>
            </div>
          </a>
        </div>
        <div id="collapseBarber" class="card card_dark collapse d-md-block" style="width: 15rem;">
          <a data-bs-toggle="modal" data-bs-target="#sobre_ferris">
            <img src="/src/assets/barbeiros/img_ferris.jpeg" class="card-img-top">
            <div class="card-body">
              <h6>Rafael Ferris — Unidade Centro (Unidade 1)</h6>
            </div>
          </a>
        </div>
      </div>
      <button class="button_gold mt-4 d-md-none" data-bs-toggle="collapse" data-bs-target="#collapseBarber">VISUALIZAR BARBEIROS</button>
    </div>

    <div class="modal fade" id="sobre_tinetti" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
      <div class="modal-dialog modal-lg">
        <div class="modal-content modal_reserve">
          <div class="modal-header">
            <h1 class="modal-title fs-5" id="exampleModalLabel">Bruno Tinetti — Unidade Centro (Unidade 1)</h1>
            <button type="button" class="btn_close ms-lg-auto" data-bs-dismiss="modal" aria-label="Close"><i class="bi bi-x-lg"></i></button>
          </div>
          <div class="modal-body">
            <p>Barbeiro experiente, o Bruno preza por um atendimento de qualidade, sempre focado em entender o que o cliente realmente busca.</p>
            <p>Atencioso e profissional, trabalha com dedicação para que cada cliente saia alinhado com seu estilo e satisfeito com o resultado.</p>
            <p>Um cara que valoriza o bom atendimento e a consistência em cada corte.</p>
          </div>
          <div class="modal-footer">
            <button type="button" class="btn btn-danger" data-bs-dismiss="modal">Voltar</button>
          </div>
        </div>
      </div>
    </div>

    <div class="modal fade" id="sobre_rafael" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
      <div class="modal-dialog modal-lg">
        <div class="modal-content modal_reserve">
          <div class="modal-header">
            <h1 class="modal-title fs-5" id="exampleModalLabel">Rafael "Feijão" - Unidade Centro (Unidade 1)</h1>
            <button type="button" class="btn_close ms-lg-auto" data-bs-dismiss="modal" aria-label="Close"><i class="bi bi-x-lg"></i></button>
          </div>
          <div class="modal-body">
            <p>Com uma pegada autêntica e personalidade forte, o Feijão traz um estilo próprio pra cadeira.</p>
            <p>Seu atendimento é descontraído, mas sempre com foco na qualidade e no resultado final.</p>
            <p>Ideal pra quem curte um corte bem feito com uma vibe diferenciada e experiência completa.</p>
          </div>
          <div class="modal-footer">
            <button type="button" class="btn btn-danger" data-bs-dismiss="modal">Voltar</button>
          </div>
        </div>
      </div>
    </div>

    <div class="modal fade" id="sobre_gabriel" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
      <div class="modal-dialog modal-lg">
        <div class="modal-content modal_reserve">
          <div class="modal-header">
            <h1 class="modal-title fs-5" id="exampleModalLabel">Gabriel - Unidade 2</h1>
            <button type="button" class="btn_close ms-lg-auto" data-bs-dismiss="modal" aria-label="Close"><i class="bi bi-x-lg"></i></button>
          </div>
          <div class="modal-body">
            <p>Jovem, mas com talento de gente grande, o Gabriel vem se destacando pelo seu degradê preciso e bem executado.</p>
            <p>Muito atencioso e dedicado, está sempre buscando evolução e aperfeiçoamento.</p>
            <p>Perfeito pra quem valoriza acabamento limpo e cortes modernos.</p>
          </div>
          <div class="modal-footer">
            <button type="button" class="btn btn-danger" data-bs-dismiss="modal">Voltar</button>
          </div>
        </div>
      </div>
    </div>

    <div class="modal fade" id="sobre_ferris" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
      <div class="modal-dialog modal-lg">
        <div class="modal-content modal_reserve">
          <div class="modal-header">
            <h1 class="modal-title fs-5" id="exampleModalLabel">Rafael Ferris — Unidade Centro (Unidade 1)</h1>
            <button type="button" class="btn_close ms-lg-auto" data-bs-dismiss="modal" aria-label="Close"><i class="bi bi-x-lg"></i></button>
          </div>
          <div class="modal-body">
            <p>Com anos de experiência, o Rafael se destaca pelo seu cuidado e capricho em cada cliente.</p>
            <p>Seu grande diferencial está nos penteados e finalizações, sempre trazendo estilo e identidade pro corte.</p>
            <p>É aquele profissional que entende o que você quer, e muitas vezes entrega ainda melhor.</p>
          </div>
          <div class="modal-footer">
            <button type="button" class="btn btn-danger" data-bs-dismiss="modal">Voltar</button>
          </div>
        </div>
      </div>
    </div>
  </main>
</template>