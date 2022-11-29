<template>
  <div id="factor">
    <div class="fondo4 oculto-impresion">
      <div class="container-fluid">
        <!--Titulo-->
        <div class="titulo3">
          <h1>
            Factor RH
            <br />
          </h1>
        </div>
        <!--Parrafo-->
        <p class="parrafo1">
          El <strong> factor Rh (Rhesus)</strong> fue descubierto en 1940
          mientras se llevaban a cabo unos experimentos con simios, el Macaco
          Rhesus, de ahí el nombre del sistema Rh. Gracias a ellos se descubrió
          la incompatibilidad de Rh y se comprobó que las personas con Rh
          negativo solo pueden recibir sangre de un donante igual a ellos.
        </p>
        <!--Titulo-->
        <h2 class="titulo4 m-5">
          ¿Conoces la importancia del factor Rh en el embarazo?
        </h2>
        <!--Parrafo-->
        <p class="parrafo1 m-5">
          Conocer nuestro grupo sanguíneo es una información relevante durante
          el embarazo, por lo cual se recomienda saber el tipo de RH del bebé y
          evitar una incompatibilidad madre e hijo, la incompatibilidad Rh se
          produce cuando el tipo de sangre de la madre es Rh negativo y el tipo
          de sangre del bebe es Rh positivo, si bien la sangre del bebe y de la
          madre raras veces suelen mezclarse, durante el parto existe una
          pequeña probabilidad que lo hagan, si esto sucede la madre producirá
          anticuerpos anti Rh positivo en respuesta a los antígenos presentes en
          su sangre, los cuales podrían atacar al bebe causando la destrucción
          de sus glóbulos rojos, por lo que es importante que mujeres Rh
          negativo se realicen pruebas durante el embarazo para comprobar el Rh
          del bebe y la presencia de anticuerpos , esto permitirá tomar las
          precauciones necesarias.
        </p>
        <!--Imagen-->
        <img
          class="imagen2 img-fluid col-12 col-sm-6"
          src="img\factor.jpg"
          alt="Antigenos"
        /><br />
        <!--Parrafo-->
        <p class="parrafo1 m-5">
          De producirse la incompatibilidad madre hijo es probable que esta
          circunstancia pueda provocar problemas en un embarazo futuro. En la
          actualidad se realiza un tratamiento preventivo para esta
          incompatibilidad a través de inyección de inmunoglobulina de Rh, que
          evita la formación de anticuerpos.
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
  text-align: center;
}
.fondo4 {
  width: 80%;
  margin: auto;
  justify-content: center;
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
  text-align: justify;
}
</style>
