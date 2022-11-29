<template>
  <div id="home">
    <div class="fondo1 oculto-impresion">
      <div class="container-fluid">
        <!--Titulo-->
        <div class="titulo1">
          <h1>
            Historia
            <br />
          </h1>
        </div>

        <!--Imagen Karl Landsteiner-->
        <div class="historia">
          <img
            class="imagen img-fluid col-12 col-sm-3 mb-5"
            src="img\Karl-Landsteiner.jpg"
            alt="imagen Karl Landsteiner"
          />

          <!--Parrafo-->
          <p class="parrafo1">
            A principios del siglo XX los médicos descubrieron que el fracaso de
            las transfusiones sanguíneas era debido a una incompatibilidad entre
            la sangre del donante y la del receptor, años más tarde el patólogo
            y biólogo Austriaco Karl Landsteiner descubrió los grupos sanguíneos
            del sistema ABO y estableció su clasificación al observar que al
            mezclar la sangre de 2 personas en ocasiones los glóbulos rojos se
            aglutinaban formando grumos.
          </p>

          <!--Imagen de Globulos Rojos-->
          <img
            class="imagen1 img-fluid col-12"
            src="img\imagen2.webp"
            alt="Globulos rojos"
          />

          <!--Parrafo-->
          <p class="parrafo2">
            En 1901 logro demostrar la existencia de al menos 3 tipos básicos de
            sangre humana que se diferenciaban por el tipo y cantidad de
            antígenos que poseían, y los clasificó en A, B, O, acuñando el
            termino ABO para designar este sistema, demostró que las
            trasfusiones dentro de esos grupos eran seguras, recibiendo el
            premio nobel de medicina por este descubrimiento en 1930. <br />
            Años más tarde en 1940 Landsteiner junto a
            <strong>Alexander Salomón Weiner</strong> biólogo y medico
            estadounidense especializado en el área de medicina forense,
            descubrieron otro antígeno en los hematíes el
            <strong>factor RH</strong>, llamado así por haberse hallado en el
            suero de conejos inmunizados con sangre de un mono indio el
            <strong>Macaco Rhesus</strong>. <br />
            Las investigaciones de Landsteiner convirtieron las transfusiones de
            sangre en un procedimiento terapéutico seguro de realizar, marcando
            así un antes y un después en el mundo de la medicina, sus estudios
            permitieron establecer los criterios de compatibilidad entre los
            seres humanos y salvar millones de vidas.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "PrimeraVista",
};
</script>

<style scoped>
* {
  padding: 0px;
  margin: 0px;
  font-family: "Open Sans", sans-serif;
  text-align: center;
}
.fondo1 {
  width: 90%;
  margin: auto;
  justify-content: center;
  background-size: 400% 400%;
}
.titulo1 {
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
.imagen {
  width: 300px;
  border-radius: 58px 0px 53px 0px;
  -moz-border-radius: 58px 0px 53px 0px;
  -webkit-border-radius: 58px 0px 53px 0px;
  border: 0px hidden #000000;
}
.imagen1 {
  width: 400px;
  border-radius: 22px 22px 22px 22px;
  -moz-border-radius: 22px 22px 22px 22px;
  -webkit-border-radius: 22px 22px 22px 22px;
  border: 0px hidden #000000;
  margin-top: 60px;
}
.parrafo2 {
  font-size: medium;
  letter-spacing: 2px;
  margin-top: 70px;
  text-align: justify;
}
.historia {
  width: 80%;
  margin: auto;
  padding-bottom: 100px;
}
.historia img.imagen {
  float: left;
  margin-right: 65px;
}
</style>
