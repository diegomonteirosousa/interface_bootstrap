# interface_bootstrap
index - carrossel bootstrap
<!DOCTYPE html>
<html lang="pt-br">
  <head>
    <!-- Meta tags Obrigatórias -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">

    <!-- Font Awesome -->
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.3.1/css/all.css" integrity="sha384-mzrmE5qonljUremFsqc01SB46JvROS7bZs3IO2EmfFsd15uHvIt+Y8vEf7N7fWAU" crossorigin="anonymous">

    <title>Carousel Slider</title>
  </head>
  <body style="padding-bottom: 80px;">
    
    <div class="container"><!--Container -->
      <div class="row"><!--Row -->
        <div class="col-sm-8 m-auto"><!--col-sm8 -->
          
          <h1>Slider simples</h1>
          <div class="carousel slide" data-ride="carousel"><!--Carousel -->
            <div class="carousel-inner"><!--Inner -->
              
              <div class="carousel-item active">
                <img src="img/imagem1.jpeg" class="img-fluid">
              </div>

              <div class="carousel-item">
                <img src="img/imagem2.jpeg" class="img-fluid">
              </div>

              <div class="carousel-item">
                <img src="img/imagem3.jpeg" class="img-fluid">
              </div>

            </div><!--/Inner -->
          </div><!--/Carousel -->
          

          <h1>Slider com controles</h1>
          <div id="carousel-controles" class="carousel slide" data-ride="carousel"><!--Carousel -->
            <div class="carousel-inner"><!--Inner -->
              
              <div class="carousel-item active">
                <img src="img/imagem1.jpeg" class="img-fluid">
              </div>

              <div class="carousel-item">
                <img src="img/imagem2.jpeg" class="img-fluid">
              </div>

              <div class="carousel-item">
                <img src="img/imagem3.jpeg" class="img-fluid">
              </div>

            </div><!--/Inner -->

            <!-- Controles -->
            <a href="#carousel-controles" class="carousel-control-prev" data-slide="prev">
              <span class="carousel-control-prev-icon"></span>
            </a>

            <a href="#carousel-controles" class="carousel-control-next" data-slide="next">
              <span class="carousel-control-next-icon"></span>
            </a>

          </div><!--/Carousel -->
          

          <h1>Slider com controles/indicadores</h1>
          <div id="carousel-indicadores" class="carousel slide" data-ride="carousel"><!--Carousel -->

            <!-- Indicadores -->
            <ol class="carousel-indicators">

              <li class="active" data-target="#carousel-indicadores" data-slide-to="0"></li>

              <li data-target="#carousel-indicadores" data-slide-to="1"></li>

              <li data-target="#carousel-indicadores" data-slide-to="2"></li>

            </ol>

            <div class="carousel-inner"><!--Inner -->
              
              <div class="carousel-item active">
                <img src="img/imagem1.jpeg" class="img-fluid">
              </div>

              <div class="carousel-item">
                <img src="img/imagem2.jpeg" class="img-fluid">
              </div>

              <div class="carousel-item">
                <img src="img/imagem3.jpeg" class="img-fluid">
              </div>

            </div><!--/Inner -->

            <!-- Controles -->
            <a href="#carousel-indicadores" class="carousel-control-prev" data-slide="prev">
              <span class="carousel-control-prev-icon"></span>
            </a>

            <a href="#carousel-indicadores" class="carousel-control-next" data-slide="next">
              <span class="carousel-control-next-icon"></span>
            </a>

          </div><!--/Carousel -->
          
           <!--carrousel 2 -->

          <h1>Slider com legendas</h1>
          <div id="carousel-legenda" class="carousel slide" data-ride="carousel"><!--Carousel -->

            <!-- Indicadores -->
            <ol class="carousel-indicators">

              <li class="active" data-target="#carousel-legenda" data-slide-to="0"></li>

              <li data-target="#carousel-legenda" data-slide-to="1"></li>

              <li data-target="#carousel-legenda" data-slide-to="2"></li>

            </ol>

            <div class="carousel-inner"><!--Inner -->
              
              <div class="carousel-item active">
                <img src="img/imagem1.jpeg" class="img-fluid">
                <div class="carousel-caption">
                  <div style="background: black; padding: 10px;">
                    <h3>Item 1</h3>
                    <p>
                      Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                    </p>
                  </div>
                </div>
              </div>
             
              <div class="carousel-item">
                <img src="img/imagem2.jpeg" class="img-fluid">
                <div class="carousel-caption">
                  <h3>Item 2</h3>
                  <p>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                  </p>
                </div>
              </div>

              <div class="carousel-item">
                <img src="img/imagem3.jpeg" class="img-fluid">
                <div class="carousel-caption">
                  <h3>Item 3</h3>
                  <p>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                  </p>
                </div>
              </div>

            </div><!--/Inner -->

            <!-- Controles -->
            <a href="#carousel-legenda" class="carousel-control-prev" data-slide="prev">
              <span class="carousel-control-prev-icon"></span>
            </a>

            <a href="#carousel-legenda" class="carousel-control-next" data-slide="next">
              <span class="carousel-control-next-icon"></span>
            </a>

          </div><!--/Carousel -->
          

        </div><!--/col-sm8 -->
      </div><!--/Row -->
    </div><!--/Container -->

    <!-- JavaScript (Opcional) -->
    <!-- jQuery primeiro, depois Popper.js, depois Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js" integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy" crossorigin="anonymous"></script>
  </body>
</html>
