<template>
  <div id="donacion">
    <div class="fondo5 oculto-impresion">
      <div class="container-fluid">
        <!--Titulo-->
        <div class="titulo3">
          <h1>
            Donación:
            <br />
          </h1>
        </div>
        <!--Parrafo-->
        <p class="parrafo1 mb-5">
          La donación de sangre es un acto voluntario altruista y sencillo el
          cual demora solo unos 30 minutos y se extraen 450 ml de sangre,
          generalmente no produce molestias, este proceso de selección del
          donante consta de distintas etapas para que la donación sea lo más
          segura posible.
        </p>
        <!--Titulo-->
        <h2 class="titulo4 mt-5"><u> Etapas de la donación: </u></h2>

        <!--Parrafo-->
        <p class="parrafo1 m-5">
          <strong>Registro de Datos personales:</strong>
          Nombre, Rut, edad, domicilio, teléfono, etc.
        </p>

        <!--Lista-->
        <ul>
          <div class="orden">
            <!--Imagen-->
            <img
              class="imagen4 img-fluid col-12 col-sm-6 mb-4"
              src="img\examen.jpg"
              alt="Examen al paciente"
            /><br />
          </div>

          <!--Lista-->
          <li class="lista1">
            <strong> Examen Físico: </strong>corresponde a la impresión general
            del posible donante, donde se tomará la presión arterial, su
            hemoglobina, peso, talla, pulso y además se realizará una pre
            clasificación de su grupo sanguíneo e inspección del sitio de
            punción.
          </li>

          <div class="orden2">
            <!--Imagen-->
            <img
              class="imagen4 img-fluid col-12 col-sm-6 mb-4"
              src="img\entrevista.jpg"
              alt="Entrevista al paciente"
            /><br />
          </div>
          <!--Lista-->
          <li class="lista1">
            <strong> Entrevista: </strong> Un profesional evaluara el estado de
            salud del posible donante y realizara algunas preguntas sobre su
            vida personal, con la finalidad de dar mayor seguridad al proceso de
            donación, tanto para el donante como para el receptor. Durante la
            entrevista podrá ser aceptado o no como como donante y podrá
            retirarse en cualquier momento del establecimiento.
          </li>

          <div class="orden">
            <!--Imagen-->
            <img
              class="imagen4 img-fluid col-12 col-sm-6 mb-5"
              src="img\flebotomia.jpg"
              alt="Flebotomia"
            /><br />
          </div>
          <!--Lista-->
          <li class="lista1">
            <strong> Flebotomía: </strong> Procedimiento por el cual se extrae
            sangre de una vena del paciente.
          </li>
        </ul>

        <!--Parrafo-->
        <p class="parrafo2">
          Es fundamental ir monitoreando al paciente durante todo el proceso
          para identificar alguna reacción adversa a la donación, finalmente se
          le entregara el documento de autoexclusión, una colación para evitar
          mareos o fatiga, además de la entrega de las indicaciones post
          donación.
        </p>
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
}
.fondo5 {
  width: 80%;
  margin: auto;
  justify-content: left;
  background-size: 400% 400%;
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
}

.parrafo2 {
  font-size: medium;
  letter-spacing: 2px;
  margin-top: 100px;
  display: inline-block;
}

.lista1 {
  width: 80%;
  margin-bottom: 80px;
  letter-spacing: 2px;
  margin-top: 20px;
}

img {
  width: 400px;
}

.orden2 {
  width: 70%;
  margin: auto;
  padding-bottom: 40px;
}

.orden2 img.imagen4 {
  float: right;
  margin-left: 65px;
}

.titulo3 {
  text-align: center;
  font-size: medium;
  letter-spacing: 2px;
  padding-bottom: 70px;
  padding-top: 70px;
}

.orden {
  width: 90%;
  margin: auto;
  padding-bottom: 50px;
}

.orden img.imagen4 {
  float: left;
  margin-right: 65px;
}
</style>
