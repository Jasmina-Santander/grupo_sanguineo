<template>
  <div id="grupo">
    <div class="fondo2 oculto-impresion">
      <div class="container-fluid">
        <!--Titulo-->
        <div class="titulo1">
          <h1>
            Grupo Sanguíneo
            <br />
          </h1>
        </div>
        <!--Parrafo-->
        <p class="parrafo1">
          Sistema que se usa para clasificar la sangre humana de diferentes
          grupos de acuerdo con la presencia o ausencia de ciertos marcadores en
          la superficie de los glóbulos rojos. En la actualidad se han definido
          más de 33 grupos sanguíneos de los cuales los que tienen mayor
          importancia son:
        </p>
        <!--Lista-->
        <ul class="one m-5">
          <strong
            ><li>ABO</li>
            <li>RH</li></strong
          >
        </ul>
        <!--Parrafo enegresido-->
        <strong>
          <p class="parrafo1 m-5">
            Clasificación de la sangre de acuerdo a las características
            presentes en la superficie de los glóbulos rojos y en el suero de la
            sangre.
          </p></strong
        >
        <!--Parrafo-->
        <p class="parrafo1 m-5">Existen 2 sistemas de grupos sanguíneos:</p>
        <!--Lista-->
        <ol class="list-group list-group-numbered">
          <li class="list-group-item"><strong> Sistema ABO: </strong></li>
          <!--Parrafo-->
          <p class="parrafo1 m-5">Hay 4 tipos de sangre A- B- O y AB</p>
          <!--Imagen-->
          <img
            class="imagen img-fluid col-12 col-sm-3"
            src="img\diagrama.jpg"
            alt="Tipos de sangre"
          />
          <!--Parrafo-->
          <p class="parrafo1 m-5">
            Tu tipo de sangre dependerá de la sangre heredada de tus padres y de
            la presencia o ausencia de ciertas proteínas presentes en los
            glóbulos rojos conocidas como antígenos que definen estos grupos y
            son responsables de que un donante y receptor sean compatibles en
            una transfusión de sangre. <br />
          </p>
          <br />
          <!--Imagen-->
          <img
            class="imagen img-fluid col-12 col-sm-6"
            src="img\grupossan.png"
            alt="Antigenos"
          /><br />
          <!--Parrafo-->
          <p class="parrafo1 m-5">
            Si eres grupo sanguíneo A significa que las superficies de tus
            glóbulos rojos presentan antígenos A. Si eres del grupo B tienes
            antígenos B. El grupo AB tiene ambos antígenos A y B. Mientras que
            el grupo O no presenta ningún antígeno, por lo cual puede ser
            transfundido de manera segura a cualquier grupo y es conocido como
            donante universal.
          </p>

          <!--Parrafo-->
          <p class="parrafo1 m-5">
            Para realizar una transfusión de sangre se emplea el sistema ABO
            para hacer coincidir el tipo de sangre del donante con el receptor.
          </p>
          <!--Tabla-->
          <div class="table-responsive">
            <table class="table1 table-bordered m-5">
              <tbody>
                <tr>
                  <td class="fila p-5">
                    <strong>Grupo O es Donante universal:</strong> Esto
                    significa que las personas que poseen este grupo sanguíneo
                    pueden donar sangre a cualquier persona.
                  </td>
                  <td class="fila p-5">
                    <strong>Grupo AB es Receptor universal:</strong> Pueden
                    aceptar sangre de todos los donantes y son llamados
                    receptores universales.
                  </td>
                  <td class="fila p-5">
                    Aquellas personas que poseen grupo A o B pueden recibir
                    sangre del mismo tipo o del grupo O.
                  </td>
                </tr>
              </tbody>
            </table>
          </div>

          <!--Lista-->
          <li class="list-group-item m-5"><strong>Sistema RH:</strong></li>
          <!--Parrafo-->
          <p class="parrafo1 m-5">
            El factor RH es una proteína hereditaria que se encuentra en la
            superficie de los glóbulos rojos, si tu sangre contiene esta
            proteína eres RH +, si esta no está presente en la sangre eres RH -.
            Aproximadamente un 95% de nuestra población posee esta proteína
            Antígeno D y son Rh +, solo un 5% de la población no la presenta y
            son Rh-.
          </p>
          <!--Imagen  icono-->
          <div class="escuchar">
            <!--Imagen-->
            <img
              class="imagen4 img-fluid col-12 col-sm-6 mt-5 p-1"
              src="img\importante.png"
              alt="Informacion Importante"
            /><br />
            <!--Parrafo enegresido-->
            <p class="parrafo3 p-5">
              <strong>
                Tu grupo sanguíneo se define por tu grupo ABO en conjunto con tu
                grupo o factor RH: <br />
                Ej: Una persona que tiene grupo A y Rh-: su grupo sanguíneo
                será: A negativo.</strong
              >
            </p>
          </div>
        </ol>
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

#grupo {
  background-color: #a60505;
  color: #f5f5db;
}

.fondo2 {
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
.one {
  list-style: inside;
}
.table1 {
  background-color: #f5f5db;
  color: black;
  margin: auto;
}

.imagen {
  margin: auto;
}

.imagen4 {
  width: 15%;
}

.parrafo3 {
  border: 1px solid rgb(0, 0, 0);
  background-color: #f5f5db;
  color: rgb(0, 0, 0);
  margin: auto;
  letter-spacing: 2px;
}
.escuchar {
  width: 70%;
  margin: auto;
  padding-bottom: 50px;
}

.escuchar img.imagen4 {
  float: left;
  margin: 10px;
}
</style>
