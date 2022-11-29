<template>
  <div id="tuGrupo">
    <div class="container text-center fondo3">
      <!--Tituloo-->
      <h1 class="titulo2">¿Conoces tu grupo sanguíneo?</h1>
      <!--Parrafo-->
      <strong>
        <p class="parrafo oculto-impresion">
          Es muy fácil solo debes ingresar tu Rut en la barra del buscador sin
          puntos y con guion <br />
          Ej: 9605009-7 <br />
          ¡Así de simple! además, podrás imprimir o descargar esta información
          si lo necesitas.
        </p></strong
      >
      <!--Formulario-->
      <div class="input-group mb-3">
        <input
          type="text"
          class="form-control"
          placeholder="Ej: 9805006-7"
          v-model="buscar"
          aria-label="Recipient's username"
          aria-describedby="basic-addon2"
        />
        <strong
          ><span class="input-group-text" id="basic-addon2"
            >Rut del paciente</span
          ></strong
        >
      </div>

      <!--Lista-->
      <ul
        class="list-group w-1"
        v-for="item in pacientesFilter"
        v-bind:key="item.id"
      >
        <!--Lista-->
        <li class="list-group-item">
          Nombre: {{ item.nombre }} - Rut: {{ item.rut }} - Grupo Sanguineo:
          {{ item.grupo }} - Edad: {{ item.edad }}
        </li>
        <a class="oculto-impresion" href="javascript:window.print()"
          ><img src="img\printer_bold.svg" alt="imprimir"
        /></a>
      </ul>
      <div class="item error" v-if="buscar && !pacientesFilter.length">
        <strong><p>“El rut no se encuentra”.</p></strong>
      </div>
      <strong
        ><p class="parrafo pb-5 oculto-impresion">
          (Ingrese RUT sin puntos y con guion)
        </p></strong
      >
    </div>
  </div>
</template>

<script>
export default {
  name: "FiltroLista",
  data: () => ({
    pacientes: [
      {
        id: "1",
        rut: "16752699-3",
        nombre: "Katherine Francisca Santander Rojas",
        grupo: "B+",
        edad: "34 años",
      },
      {
        id: "2",
        rut: "17619702-1",
        nombre: "Jasmina Andrea Santander Rojas",
        grupo: "O+",
        edad: "29 años",
      },
      {
        id: "3",
        rut: "16752699-8",
        nombre: "Cecilia Monica Rojas Sepulveda",
        grupo: "B+",
        edad: "66 años",
      },
      {
        id: "4",
        rut: "16752699-2",
        nombre: "Raul Francisco Santander Hurtado",
        grupo: "O+",
        edad: "68 años",
      },
      {
        id: "5",
        rut: "16752699-1",
        nombre: "Karen Ximena Santander Rojas",
        grupo: "O+",
        edad: "39 años",
      },
    ],

    buscar: "",
  }),

  computed: {
    pacientesFilter() {
      return this.pacientes.filter((item) => {
        return item.rut === this.buscar;
      });
    },
  },
};
</script>

<style>

.fondo3 {
  background-image: url("../assets/fondo.jpg");
  background-repeat: no-repeat;
  background-size: cover;      
background-position: bottom center;
  color: rgb(0, 0, 0);
  padding-bottom: 60px;
  margin-top: 130px;
  margin-bottom: 100px;
  box-shadow: -13px 13px 17px -3px rgba(7, 7, 7, 0.274);
}

.parrafo {
  font-size: 20px;
  text-shadow: 1px 0 0 #000;
}
.titulo2 {
  margin-top: 150px;
  padding-top: 80px;
  margin-bottom: 80px;
}
.form-control {
  border: 1px solid #f25e5e;
}
.input-group-text {
  background-color: #730707;
  color: rgb(255, 255, 255);
  font-weight: bold;
}

@media print {
  .oculto-impresion,
  .oculto-impresion * {
    display: none !important;
  }
}
</style>
