<template>
  <div id="footer">
    <!-- Footer -->
    <footer class="text-center oculto-impresion">
      <!-- Section: Social media -->
      <section
        class="d-flex justify-content-center justify-content-lg-between p-4 border-bottom"
      >
        <!-- Left -->
        <div class="me-5 d-none d-lg-block">
          <span
            >Conéctate con nosotros, para estar al tanto de las novedades:</span
          >
        </div>
        <!-- Right -->
      </section>
      <!-- Section: Social media -->

      <!-- Section: Links  -->
      <section class="">
        <div class="container text-center text-md-start mt-5">
          <!-- Grid row -->
          <div class="row mt-3">
            <!-- Grid column -->
            <div class="col-md-3 col-lg-4 col-xl-3 mx-auto mb-4">
              <!-- Content -->
              <h6 class="text-uppercase fw-bold mb-4">
                Proyecto Grupo Sanguíneo
              </h6>
              <p>
                Página elaborada para la obtención de su grupo sanguíneo y
                entregar información de una forma fácil y clara.
              </p>
              <img
                class="imagen img-fluid col-5 col-sm-4 m-5 justify-content-center"
                src="img\icono.png"
                alt="Antigenos"
              />
            </div>
            <!-- Grid column -->

            <!-- Grid column -->
            <div class="col-md-3 col-lg-3 col-xl-3 mx-auto mb-6">
              <!-- Links -->
              <h6 class="text-uppercase fw-bold mb-4">
                Banco de sangre Valparaíso:
              </h6>
              <p>
                <!--Imagen-->
                <img
                  class="imagenF img-fluid col-12 col-sm-6"
                  src="img\icono1.jpg"
                  alt="Antigenos"
                />
                <a
                  href="http://www.centrodesangrevalparaiso.cl/"
                  class="text-reset"
                  >Centro de sangre Valparaíso</a
                >
              </p>
              <p>
                <img
                  class="imagenF img-fluid col-12 col-sm-6"
                  src="img\icono2.png"
                  alt="Antigenos"
                />
                <a href="https://www.minsal.cl/" class="text-reset">Minsal</a>
              </p>
              <p>
                <img
                  class="imagenF img-fluid col-12 col-sm-6"
                  src="img\icono3.png"
                  alt="Antigenos"
                />
                <a
                  href="https://www.redsaludpopular.cl/laboratorio-clinico/"
                  class="text-reset"
                  >Red Salud Popular</a
                >
              </p>
              <p>
                <img
                  class="imagenF img-fluid col-12 col-sm-6"
                  src="img\icono4.png"
                  alt="Antigenos"
                />
                <a
                  href="https://cmvalparaiso.cl/tag/laboratorio-clinico-popular/"
                  class="text-reset"
                  >Laboratorio Clínico Popular</a
                >
              </p>
            </div>
            <!-- Grid column -->

            <!-- Grid column -->
            <div class="col-md-4 col-lg-3 col-xl-3 mx-auto mb-4">
              <!-- Links -->
              <h6 class="text-uppercase fw-bold mb-4">Noticias de interés:</h6>
              <ul class="lista mt-4">
                <li class="lista mb-4">
                  <a
                    href="https://www.t13.cl/noticia/mundo/bbc/kell-kidd-duffy-y-otros-grupos-sanguineos-que-
quizas-no-conocias-11-11-2022"
                    class="text-reset"
                    >Kell, Kidd, Duffy y otros grupos sanguíneos</a
                  >
                </li>
                <li class="lista mb-4">
                  <a
                    href="https://www.t13.cl/noticia/mundo/coronavirus-influyen-grupos-sanguineos-gravedad-
covid-19"
                    class="text-reset"
                    >Grupos sanguíneos y gravedad del COVID-19</a
                  >
                </li>
                <li class="lista mb-4">
                  <a
                    href="https://www.t13.cl/videos/nacional/video-investigacion-asegura-grupo-sanguineo-
podria-definir-riesgo-coronavirus"
                    class="text-reset"
                    >Investigación grupo y riesgo ante el coronavirus</a
                  >
                </li>
              </ul>
            </div>
            <!-- Grid column -->
          </div>
          <!-- Grid row -->
        </div>
      </section>
    </footer>
    <!-- Footer -->
  </div>
</template>

<script>
export default {
  name: "footer",
};
</script>

<style scoped>
* {
  padding: 0px;
  margin: 0px;
  font-family: "Open Sans", sans-serif;
}
footer {
  width: 100%;
  justify-content: center;
  background-size: 400% 400%;
  background-color: #a60505;
  color: #f5f5db;
}
.imagenF {
  width: 15%;
  margin: 10px;
}
</style>
