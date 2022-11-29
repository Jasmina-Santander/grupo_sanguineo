<template>
  <div id="transfusion">
    <div class="fondo4 oculto-impresion">
      <div class="container-fluid">
        <!--Titulo-->
        <div class="titulo3">
          <h1>
            Transfusión:
            <br />
          </h1>
        </div>

        <!--Parrafo-->
        <p class="parrafo1 mb-5">
          La medicina transfusional es la rama de la medicina que se ocupa de
          los procesos de obtención análisis y tratamiento conservación y
          almacenamiento de la sangre para su posterior transfusión de esta o de
          alguno de sus hemo componentes.
        </p>
        <!--Titulo-->
        <h2 class="titulo4 mt-5">Terapia transfusional:</h2>
        <!--Parrafo-->
        <p class="parrafo1 mt-5">
          La transfusión es el propósito final de la medicina transfusional es
          la transferencia de la sangre o de uno de sus componentes de un
          donante a un receptor.
        </p>

        <!--Titulo-->
        <h2 class="titulo4 mt-5">Compatibilidad de grupos sanguíneos:</h2>

        <div class="Compatibilidad">
          <!--Imagen-->
          <img
            class="imagen2 img-fluid col-12 col-sm-6"
            src="img\transfusion.png"
            alt="Transfusion de Sangre"
          /><br />
        </div>
        <!--Parrafo-->
        <p class="parrafo2">
          Una transfusión de sangre es más segura cuando el grupo sanguíneo de
          la sangre transfundida coincide con el grupo sanguíneo y el factor Rh
          del receptor, si las personas reciben sangre de alguien con un tipo de
          sangre diferente, esto provocaría una reacción adversa del sistema
          inmunitario, una incompatibilidad ABO.
        </p>

        <!--Titulo-->
        <h3 class="titulo4 mt-5 mb-5">
          Tabla de compatibilidad entre grupos sanguíneos:
        </h3>

        <!--Imagen-->
        <img
          class="imagen3 img-fluid col-12 col-sm-6 mb-5"
          src="img\donar.jpg"
          alt="Compatibilidad donacion"
        /><br />
        <div class="Importante">
          <!--Imagen-->
          <img
            class="imagen4 img-fluid col-12 col-sm-6 mt-5 p-1"
            src="img\importante.png"
            alt="Informacion Importante"
          /><br />
          <!--Parrafo-->
          <p class="parrafo3 p-5">
            En la mayoría de los casos los pacientes reciben sangre de su mismo
            grupo sanguíneo, sin embargo, en caso de emergencias si la persona
            se encuentra en riesgo vital se utilizará sangre O-.
          </p>
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
}
#transfusion {
  background-color: #a60505;
  color: #f5f5db;
}
.fondo4 {
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
  width: 80%;
  margin-bottom: 100px;
  letter-spacing: 2px;
}
.imagen2 {
  width: 200px;
}
.parrafo3 {
  border: 1px solid rgb(255, 255, 255);
  margin: auto;
  letter-spacing: 2px;
}
.Compatibilidad {
  width: 80%;
  margin: auto;
  padding-bottom: 40px;
}
.Compatibilidad img.imagen2 {
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
.imagen4 {
  width: 15%;
}
.Importante {
  width: 70%;
  margin: auto;
  padding-bottom: 50px;
}
.Importante img.imagen4 {
  float: left;
  margin: 10px;
}
</style>
