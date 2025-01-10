<nav class="navbar navbar-expand-lg cor_cabecalho">
  <div class="container-fluid margem_logo">
    <a class="navbar-brand" href="#" onclick="location.reload()">
      <img alt="img_logo" src="./imagens/LOGO FINAL.png">
    </a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
      aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon navbar-dark"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav mx-auto gap_cabecalho ">
        <li class="nav-item">
          <a class="nav-link cabecalho font" href="#HOME">
     <!DOCTYPE html>
<html lang="pt-br">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/css/bootstrap.min.css" rel="stylesheet"
    integrity="sha384-rbsA2VBKQhggwzxH7pPCaAqO46MgnOM80zW1RWuH61DGLwZJEdK2Kadq2F9CUG65" crossorigin="anonymous">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Lexend+Zetta:wght@100..900&display=swap" rel="stylesheet">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100..900;1,100..900&display=swap"
    rel="stylesheet">
  <link rel="stylesheet" href="./style.css">
  <title>Dr. Andreia Sousa</title>
</head>
<header class="cabecalho">

</header>

<body>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/js/bootstrap.bundle.min.js"
    integrity="sha384-kenU1KFdBIe4zVF0s0G1M5b4hcpxyD9F7jL+jjXkk+Q2h455rYXK/7HAuoJl+0I4"
    crossorigin="anonymous"></script>
  <main>
    <!-- CABECALHO RESPONSIVO COM bootstrap (INICIO)-->
    <nav class="navbar teste navbar-expand-lg cor_cabecalho">
      <div class="container-fluid margem_logo">
        <a class="navbar-brand" href="#" onclick="location.reload()">
          <img alt="img_logo" src="./imagens/LOGO FINAL.png">
        </a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
          aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon navbar-dark"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav mx-auto gap_cabecalho ">
            <li class="nav-item">
              <a class="nav-link cabecalho font" href="#HOME">
                HOME
              </a>
            </li>
            <li class="nav-item">
              <a class="nav-link cabecalho fs-6 font" href="#SOBRE">
                SOBRE NÓS
              </a>
            </li>
            <li class="nav-item">
              <a class="nav-link cabecalho fs-6 font" href="#AREA">
                ÁREAS DE ATUAÇÃO
              </a>
            </li>
            <li class="nav-item">
              <a class="nav-link cabecalho fs-6 font" href="#CONTATO">
                CONTATO
              </a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </main>
  <!-- CABECALHO RESPONSIVO COM bootstrap (FIM) -->
  <main>
    <section id="HOME">
      <div class="row">
        <div class=" font_2 conteudo_home col-sm-12 col-md-6 col-lg-6">
          <p class="fs-1">
            Estamos <strong class="strong"> comprometidos </strong> em colaborar diretamente com você
          </p>
          <p class="tam_texto_home hidden">
            Visando alcançar <strong class="strong"> os resultados </strong> mais vantajosos para o seu sucesso. Com uma
            abordagem focada na <strong class="strong"> excelência </strong> e na constante melhoria.
          </p>
        </div>
        <div class=" img_home col-12 col-sm-12 col-md-6 col-lg-6">
          <img alt="balanca_img" src="./imagens/BALANCA.png" class="img-fluid">
        </div>
      </div>
    </section>
    <section id="SOBRE">
      <div class="row">
        <div class=" font_2 conteudo_sobre col-sm-12 col-md-6 col-lg-6">
          <div class="tam_texto_sobre hidden">
            <p>
              Operamos com <strong> eficiência </strong>, garantindo que cada passo seja eficaz, fundamentado em um
              profundo conhecimento e pautado por <strong> integridade </strong> e <strong> idoneidade </strong>.
            </p>
            <p>
              <strong> Marque uma visita </strong>, entre em contato via <strong> WhatsApp </strong> ou <strong> e-mail
              </strong> e confie em nós para ser seu parceiro de confiança em sua trajetória pessoal ou empresarial.
            </p>
          </div>
        </div>
        <div class=" img_sobre col-12 col-sm-12 col-md-6 col-lg-6">
          <img alt="apertodemaos_img" src="./imagens/MAOS.jpeg" class="img-fluid">
        </div>
      </div>
    </section>
    <section id="AREA">
      <h3 class="font_2 display-1 mb-5 text-center hidden">
        ÁREAS DE ATUAÇÃO
      </h3>
      <!-- CARDS COM BOOTSTRAP (INICIO) -->
      <div class="cards">
        <div class="row text-center px-5 mb-4">
          <div class="padding_card col-12 col-sm-12 col-md-4 col-lg-4 hidden">
            <div class="card cor_cards">
              <img src="./imagens/CARD CIVEL.png" class="card-img-top" alt="img_card">
              <div class="card-body">
                <h5 class="card-title font">DIREITO CÍVEL</h5>
                <p class="card-text my-3 font_2">
                  O Direito Civil é a área que regula as relações entre pessoas, tanto físicas quanto jurídicas. Trata de
                  assuntos como contratos, propriedade, família e obrigações.
                </p>
                <button type="button" class="btn btn-outline-light font_2" data-bs-toggle="modal"
                  data-bs-target="#Modal_1">
                  Saiba Mais
                </button>
              </div>
            </div>
          </div>
  
          <div class="padding_card col-12 col-sm-12 col-md-4 col-lg-4 hidden" >
            <div class="card cor_cards">
              <img src="./imagens/CARD TRT.png" class="card-img-top" alt="img_card">
              <div class="card-body">
                <h5 class="card-title font">DIREITO TRABALHISTA</h5>
                <p class="card-text my-3 font_2">
                  O Direito Trabalhista é a área que regula as relações entre empregadores e empregados. Trata dos
                  direitos e deveres de ambos, garantindo condições justas.
                </p>
                <button type="button" class="btn btn-outline-light font_2" data-bs-toggle="modal"
                  data-bs-target="#Modal_2">
                  Saiba Mais
                </button>
              </div>
            </div>
          </div>
  
          <div class="padding_card col-12 col-sm-12 col-md-4 col-lg-4 hidden">
            <div class="card cor_cards">
              <img src="./imagens/CARD MATERNIDADE.png" class="card-img-top" alt="img_card">
              <div class="card-body">
                <h5 class="card-title font font_2"> LICENÇA MATERNIDADE </h5>
                <p class="card-text my-3 font_2">
                  A licença maternidade é um direito que regulamenta o afastamento remunerado das trabalhadoras gestantes
                  para recuperação e cuidados com o recém-nascido.
                </p>
                <button type="button" class="btn btn-outline-light font_2" data-bs-toggle="modal"
                  data-bs-target="#Modal_3">
                  Saiba Mais
                </button>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- CARDS COM BOOTSTRAP (FIM) -->
      <!-- MODAL CIVEL (INICIO) -->
      <div class="modal fade" id="Modal_1" tabindex="-1" aria-labelledby="exampleModalLabel_1" aria-hidden="true">
        <div class="modal-dialog">
          <div class="modal-content cor_modal">
            <div class="modal-header">
              <h5 class="modal-title font" id="exampleModalLabel_1">DIREITO CÍVEL</h5>
            </div>
            <div class="modal-body">
              <div class="accordion" id="accordionExample1">
                <div class="accordion-item">
                  <h2 class="accordion-header" id="headingOne1">
                    <button class="accordion-button font" type="button" data-bs-toggle="collapse"
                      data-bs-target="#collapseOne1" aria-expanded="true" aria-controls="collapseOne1">
                      Família e Suceções
                    </button>
                  </h2>
                  <div id="collapseOne1" class="accordion-collapse collapse show" aria-labelledby="headingOne1"
                    data-bs-parent="#accordionExample1">
                    <div class="accordion-body">
                      <p class="font_2">
                        -Inventário judicial e extrajudicial de bens.<br />
                        -Divórcio litigioso e consensual.<br />
                        -Guardas, regulamentações de visitas e pensões alimentícia de menores.<br />
                        -Alimentos Avoengos.<br />
                        -Alimentos gravídicos.<br />
                        -Reconhecimento de paternidade (post mortem).<br />
                        -Dissolução de união estável.<br />
                        -Planejamento patrimonial e sucessório.<br />
                        -Alteração de regime de bens de casamento.<br />
                        -Reconhecimento de filiação.<br />
                        -Exoneração de Alimentos.<br />
                      </p>
                    </div>
                  </div>
                </div>
                <div class="accordion-item">
                  <h2 class="accordion-header" id="headingTwo1">
                  </h2>
                  <div id="collapseTwo1" class="accordion-collapse collapse" aria-labelledby="headingTwo1"
                    data-bs-parent="#accordionExample1">
                    <div class="accordion-body">
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="modal-footer">
              <button type="button" class="btn btn-outline-light font_2" data-bs-dismiss="modal">Fechar</button>
            </div>
          </div>
        </div>
      </div>
      <!-- MODAL CIVEL (FIM) -->
      <!-- MODAL TRABALHISTA (INICIO) -->
      <div class="modal fade" id="Modal_2" tabindex="-1" aria-labelledby="exampleModalLabel_2" aria-hidden="true">
        <div class="modal-dialog">
          <div class="modal-content cor_modal">
            <div class="modal-header">
              <h5 class="modal-title font" id="exampleModalLabel_2">DIREITO TRABALHISTA</h5>
            </div>
            <div class="modal-body">
              <div class="accordion" id="accordionExample2">
                <div class="accordion-item">
                  <h2 class="accordion-header" id="headingOne2">
                    <button class="accordion-button font" type="button" data-bs-toggle="collapse"
                      data-bs-target="#collapseOne2" aria-expanded="true" aria-controls="collapseOne2">
                      Empregadores
                    </button>
                  </h2>
                  <div id="collapseOne2" class="accordion-collapse collapse show" aria-labelledby="headingOne2"
                    data-bs-parent="#accordionExample2">
                    <div class="accordion-body">
                      <p class="font_2">
                        - Consultoria Preventiva. <br />
                        - Atuação Administrativa e Jurisdicional. <br />
                        - Desenvolvimento e Atuação em Proposta de Acordo. <br />
                        - Análise de Contratos de Trabalho e Prestação de Serviços. <br />
                        - Discriminação de verbas de Acordos Trabalhistas. <br />
                        - Adicional por Acúmulo ou Desvio de Função. <br />
                        - Elaboração de petição inicial. <br />
                        - Elaboração de defesa. <br />
                        - Instrução processual e audiências. <br />
                        - Área recursal. <br />
                        - Execução de sentença. <br />
                      </p>
                    </div>
                  </div>
                </div>
                <div class="accordion-item">
                  <h2 class="accordion-header" id="headingTwo2">
                    <button class="accordion-button collapsed font" type="button" data-bs-toggle="collapse"
                      data-bs-target="#collapseTwo2" aria-expanded="false" aria-controls="collapseTwo2">
                      Funcionários
                    </button>
                  </h2>
                  <div id="collapseTwo2" class="accordion-collapse collapse" aria-labelledby="headingTwo2"
                    data-bs-parent="#accordionExample2">
                    <div class="accordion-body">
                      <p class="font_2">
                        -Reclamações trabalhistas. <br />
                        -Atraso de pagamento de salário. <br />
                        -Reconhecimento de vínculo empregatício. <br />
                        -Reconhecimento de vinculo empregatício de sócios de empresa.<br />
                        -Reversão de demissão por justa causa. <br />
                        -Relação de emprego. <br />
                        -Acidente do trabalho. <br />
                        -LER - lesão por esforço repetitivo. <br />
                        -Responsabilidade das empresas. <br />
                        -Fraudes trabalhistas. <br />
                        -Rescisão indireta do contrato de trabalho. <br />
                        -Rescisão por força maior indevidamente utilizada. <br />
                        -Assédio moral e sexual. <br />
                        -Preconceito e discriminação no ambiente de trabalho. <br />
                        -Adicionais de periculosidade e insalubridade. <br />
                        -Adicional noturno. <br />
                        -Acúmulo de função e desvio de função. <br />
                        -Férias em dobro. <br />
                        -Horas extras. <br />
                        -Equiparação salarial. <br />
                        -Reintegração de gestantes. <br />
                        -Reintegração de funcionários estáveis. <br />
                        -Estabilidade da gestante. <br />
                        -Participação dos trabalhadores nos lucros e resultados. <br />
                        -Luvas, prêmios e gratificações de função. <br />
                        -Estabilidade. <br />
                        -Rebaixamento de cargo. <br />
                        -Doenças profissionais e doenças no trabalho. <br />
                      </p>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="modal-footer">
              <button type="button" class="btn btn-outline-light font_2" data-bs-dismiss="modal">Fechar</button>
            </div>
          </div>
        </div>
      </div>
      <!-- MODAL TRABALHISTA (FIM) -->
      <!-- MODAL LICENÇA MATERNIDADE (INICIO) -->
      <div class="modal fade" id="Modal_3" tabindex="-1" aria-labelledby="exampleModalLabel_3" aria-hidden="true">
        <div class="modal-dialog">
          <div class="modal-content cor_modal">
            <div class="modal-header">
              <h5 class="modal-title font" id="exampleModalLabel_2"> LICENÇA MATERNIDADE </h5>
            </div>
            <div class="modal-body">
              <div class="accordion" id="accordionExample2">
                <div class="accordion-item">
                  <h2 class="accordion-header" id="headingOne2">
                    <button class="accordion-button font" type="button" data-bs-toggle="collapse"
                      data-bs-target="#collapseOne2" aria-expanded="true" aria-controls="collapseOne2">
                      QUEM TEM DIREITO?
                    </button>
                  </h2>
                  <div id="collapseOne2" class="accordion-collapse collapse show" aria-labelledby="headingOne2"
                    data-bs-parent="#accordionExample2">
                    <div class="accordion-body">
                      <p class="font_2">
                        -INSS - Auxílio Maternidade Quem tem direito: Empregada MEI (Microempreendedor
                        Individual).<br />
                        -Pessoa desempregada, desde que mantenha qualidade de segurado.<br />
                        -Empregada doméstica.<br />
                        -Empregada que adotar criança.<br />
                        -Contribuinte individual.<br />
                        -Empregado doméstico.<br />
                        -Trabalhador avulso.<br />
                        -Segurado facultativo.<br />
                      </p>
                    </div>
                  </div>
                </div>
                <div class="accordion-item">
                  <h2 class="accordion-header" id="headingTwo2">
                  </h2>
                  <div id="collapseTwo2" class="accordion-collapse collapse" aria-labelledby="headingTwo2"
                    data-bs-parent="#accordionExample2">
                    <div class="accordion-body">
                      <p class="font_2">
                      </p>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="modal-footer">
              <button type="button" class="btn btn-outline-light font_2" data-bs-dismiss="modal">Fechar</button>
            </div>
          </div>
        </div>
      </div>
      <!-- MODAL LICENÇA MATERNIDADE (FIM) -->
    </section>
    <section id="CONTATO" >
      <div class="row">
        <div class="col-12 col-sm-12 col-md-12 col-lg-12 botoes_contato margin-top-btn">
          <p class="txt-adv font margin-right-font-txt font-txt_cell hidden ">
            Marque uma consultoria, entre em contato via WhatsApp ou e-mail
          </p>
          <a class="btn btn-outline-light btn-cor width-height-btn margin-left-btn width-height-btn_cell margin-bnt_cell font padding-btn_icons padding-btn_icons_cell"
            type="button" href="https://wa.me/5561996196981" target="_blank">
            <img alt="logo_whats" src="./imagens/whatsapp_contato.png">
            WHATSAPP
          </a>
          <a class=" btn btn-outline-light btn-cor width-height-btn margin-left-btn width-height-btn_cell margin-bnt_cell font padding-btn_icons padding-btn_icons_cell"
          type="button" href="mailto:advandreiasslopes@gmail.com">
            <img alt="logo_email" src="./imagens/gmail_contato.png">
            E-MAIL
          </a>
        </div>
      </div>
    </section>
    <footer class="rodape">
      <div class="col-12 col-sm-12 col-md-6 col-lg-6">
        <p>
          © 2024 Durt. Todos os direitos reservados.
        </p>
        <p>
          Contatos: N°: (61) 99619 - 6981 / E-mail: ADVANDREIASSLOPES@GMAIL.COM
        </p>
      </div>
      <button id="scrollTopButton">
        <img alt="botao_img" src="./imagens/SETA.png">
      </button>
      <a class="scroll-link" id="scrollLink" href="https://wa.me/5561996196981" target="_blank">
        <div>
          <img alt="whats_img" width="50" src="./imagens/whatsapp.png">
        </div>
      </a>
    </footer>
  </main>
  <!-- BOTAO SCROLL PARA O TOP COM JS (INICIO) -->
  <script>

    var scrollToButton = document.getElementById("scrollTopButton");
    var docElement = document.documentElement;

    function scrolltoTop() {
      docElement.scrollTo({
        top: 0,
        behavior: "smooth"
      })
    }

    function handleScroll() {
      var scrollTotal = docElement.scrollHeight - docElement.clientHeight;
      var count = docElement.scrollTop / scrollTotal
      if (count > 0.2) {
        scrollToButton.classList.add("showBtn")
      } else {
        scrollToButton.classList.remove("showBtn")
      }
    }

    document.addEventListener("scroll", handleScroll)
    scrollToButton.addEventListener("click", scrolltoTop);
  </script>
  <!-- BOTAO SCROLL PARA O TOP COM JS (FIM) -->
  <!-- BOTAO WHATSAPP APARECE EM CERTO PONTO DO SCROLL JS (INICIO) -->
  <script>
    window.addEventListener('scroll', function () {
      const scrollLink = document.getElementById('scrollLink');
      const scrollPosition = window.scrollY || document.documentElement.scrollTop;

      // Altere 500 para a posição em pixels que você deseja que o link apareça
      if (scrollPosition > 800) {
        scrollLink.classList.add('show');
      } else {
        scrollLink.classList.remove('show');
      }
    });
  </script>
  <!-- BOTAO WHATSAPP APARECE EM CERTO PONTO DO SCROLL JS (FIM) -->
  <!-- ANIMAÇÃO COM JS NA PAGINA (INICIO) -->
  <script>

    const myObserver = new IntersectionObserver( (entries) => {
      entries.forEach( (entry) => {
        if (entry.isIntersecting){
          entry.target.classList.add('show')
        } else {
          entry.target.classList.remove('show')
        }
      })
    })

    const elements = document.querySelectorAll('.hidden')
    
    elements.forEach( (element) => myObserver.observe(element) )
    

  </script>
  <!-- ANIMAÇÃO COM JS NA PAGINA (FIM) -->
</body>

