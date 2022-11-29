<template>
  <!--Seccion Portada-->
  <section class="portada oculto-impresion">
    <div class="container"></div>
  </section>
</template>

<script>
export default {
  name: "Portada",
};
</script>

<style scoped>
/*Estilo Fondo de pagina*/
.portada {
  height: 90vh;
  background-image: url("../assets/Banner.jpg");
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-position: bottom;
  background-size: cover;
}
.container {
  padding-top: 15%;
  padding-left: 20%;
  font-family: sans-serif;
  font-size: 18px;
  font-weight: 400;
}
</style>
