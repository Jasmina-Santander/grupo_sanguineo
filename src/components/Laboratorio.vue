<template>
  <div id="laboratorio">
    <div class="fondo6 oculto-impresion">
      <div class="container-fluid">
        <!--Titulo-->
        <div class="titulo3">
          <h1>
            Imágenes de laboratorio
            <br />
          </h1>
        </div>
        <!--Parrafo-->
        <p class="parrafo1 mb-5">
          El examen para determinar el grupo sanguíneo se denomina tipificación
          o clasificación ABO-Rh, esta es la prueba más importante de realizar
          antes de una transfusión ya que el transfundir glóbulos rojos ABO
          incompatibles puede ser mortal o causar una reacción hemolítica grave
          o CID y falla renal, existen distintas técnicas para la clasificación
          de los grupos sanguíneos.
        </p>

        <!--Carusel de imagenes-->
        <div
          id="carouselExampleCaptions"
          class="carousel slide"
          data-bs-ride="carousel"
        >
          <div class="carousel-indicators">
            <button
              type="button"
              data-bs-target="#carouselExampleCaptions"
              data-bs-slide-to="0"
              class="active"
              aria-current="true"
              aria-label="Slide 1"
            ></button>
            <button
              type="button"
              data-bs-target="#carouselExampleCaptions"
              data-bs-slide-to="1"
              aria-label="Slide 2"
            ></button>
            <button
              type="button"
              data-bs-target="#carouselExampleCaptions"
              data-bs-slide-to="2"
              aria-label="Slide 3"
            ></button>
            <button
              type="button"
              data-bs-target="#carouselExampleCaptions"
              data-bs-slide-to="3"
              aria-label="Slide 4"
            ></button>
            <button
              type="button"
              data-bs-target="#carouselExampleCaptions"
              data-bs-slide-to="4"
              aria-label="Slide 5"
            ></button>
            <button
              type="button"
              data-bs-target="#carouselExampleCaptions"
              data-bs-slide-to="5"
              aria-label="Slide 6"
            ></button>
            <button
              type="button"
              data-bs-target="#carouselExampleCaptions"
              data-bs-slide-to="6"
              aria-label="Slide 7"
            ></button>
            <button
              type="button"
              data-bs-target="#carouselExampleCaptions"
              data-bs-slide-to="7"
              aria-label="Slide 8"
            ></button>
          </div>
          <div class="carousel-inner">
            <div class="carousel-item active" data-bs-interval="10000">
              <img src="img\1.jpg" class="d-block w-100" alt="Laboratorio" />
              <div class="carousel-caption d-none d-md-block">
                <h5 class="texto">
                  Determinación de grupo sanguíneo en lámina:
                </h5>
                <p class="texto">
                  Es utilizada como técnica para la pre-clasificación de grupo
                  sanguíneo.
                </p>
              </div>
            </div>
            <div class="carousel-item" data-bs-interval="10000">
              <img src="img\2.jpg" class="d-block w-100" alt="Laboratorio" />
              <div class="carousel-caption d-none d-md-block">
                <h5 class="texto">Sueros clasificadores o antisueros:</h5>
              </div>
            </div>
            <div class="carousel-item" data-bs-interval="10000">
              <img src="img\3.jpg" class="d-block w-100" alt="Laboratorio" />
              <div class="carousel-caption d-none d-md-block">
                <h5 class="texto">Pre clasificación en lamina:</h5>
                <p class="texto">
                  Rotulamos la placa con los grupos sanguíneos ABO y Rh y
                  agregamos 1 gota de sangre y 2 de cada antisuero respectivo
                  mezclamos y observamos el resultado. Una vez transcurrido el
                  tiempo se observa las muestras donde se presenta aglutinación.
                </p>
              </div>
            </div>
            <div class="carousel-item" data-bs-interval="10000">
              <img src="img\5.jpg" class="d-block w-100" alt="Laboratorio" />
              <div class="carousel-caption d-none d-md-block">
                <h5 class="texto">Tarjetas gel:</h5>
                <p class="texto">
                  Soporte plástico constituido por 6 a 8 microtúbulos, formados
                  por una columna y una cámara de dispensación/ incubación.
                </p>
              </div>
            </div>
            <div class="carousel-item" data-bs-interval="10000">
              <img src="img\6.jpg" class="d-block w-100" alt="Laboratorio" />
              <div class="carousel-caption d-none d-md-block">
                <h5 class="texto">Centrifuga para Tarjeta Gel</h5>
              </div>
            </div>
            <div class="carousel-item" data-bs-interval="10000">
              <img src="img\7.jpg" class="d-block w-100" alt="Laboratorio" />
              <div class="carousel-caption d-none d-md-block">
                <h5 class="texto">Interpretacion de Tarjeta Gel</h5>
              </div>
            </div>
            <div class="carousel-item" data-bs-interval="10000">
              <img src="img\8.jpg" class="d-block w-100" alt="Laboratorio" />
              <div class="carousel-caption d-none d-md-block">
                <h5 class="texto">Determinación en tubo</h5>
              </div>
            </div>
            <div class="carousel-item" data-bs-interval="10000">
              <img src="img\9.jpg" class="d-block w-100" alt="Laboratorio" />
              <div class="carousel-caption d-none d-md-block">
                <h5 class="texto">Glóbulos rojos testigos A y B:</h5>
                <p class="texto">
                  Corresponden a glóbulos rojos de fenotipos conocidos que se
                  utilizan como reactivos para evidenciar anticuerpos naturales
                  del sistema ABO.
                </p>
              </div>
            </div>
          </div>
          <button
            class="carousel-control-prev"
            type="button"
            data-bs-target="#carouselExampleCaptions"
            data-bs-slide="prev"
          >
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
          </button>
          <button
            class="carousel-control-next"
            type="button"
            data-bs-target="#carouselExampleCaptions"
            data-bs-slide="next"
          >
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
          </button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Grupo",
};
</script>

<style scoped>
* {
  padding: 0px;
  margin: 0px;
  font-family: "Open Sans", sans-serif;
  text-align: center;
}
.fondo6 {
  width: 80%;
  margin: auto;
  justify-content: center;
  background-size: 400% 400%;
  margin-bottom: 150px;
}

.titulo3 {
  text-align: center;
  font-size: medium;
  letter-spacing: 2px;
  padding-bottom: 70px;
  padding-top: 70px;
}

.parrafo1 {
  font-size: medium;
  letter-spacing: 2px;
  text-align: justify;
}

.carousel {
  width: 70%;
  margin-left: 15%;
}

.texto {
  color: rgb(255, 255, 255);
  letter-spacing: 2px;
  text-shadow: 2px 0 0 #000, -2px 0 0 #000, 0 2px 0 #000, 0 -2px 0 #000,
    1px 1px #000, -1px -1px 0 #000, 1px -1px 0 #000, -1px 1px 0 #000;
}
</style>
