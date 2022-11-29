<template>
  <!--Menu-->
  <nav class= "oculto-impresion navbar navbar-expand-lg navbar-light">
    <div class="container">
      <a class="navbar-brand home p-3" href=""
        ><router-link to="/"> Home </router-link></a
      >
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item dropdown">
            <a
              class="nav-link dropdown-toggle"
              href="#"
              role="button"
              data-bs-toggle="dropdown"
              aria-expanded="false"
            >
              Grupos Sanguíneos
            </a>
            <ul class="dropdown-menu item">
              <li>
                <a class="dropdown-item" href="#home"
                  ><router-link to="/"> Historia </router-link></a
                >
              </li>
              <li>
                <a class="dropdown-item" href="#grupo"
                  ><router-link to="/"> Grupos </router-link></a
                >
              </li>
              <li><hr class="dropdown-divider" /></li>
              <li>
                <a class="dropdown-item" href="#factor"
                  ><router-link to="/"> Factor RH </router-link></a
                >
              </li>
            </ul>
          </li>
          <li class="nav-item dropdown item">
            <a
              class="nav-link dropdown-toggle"
              href="#"
              role="button"
              data-bs-toggle="dropdown"
              aria-expanded="false"
            >
              Consulta tu grupo
            </a>
            <ul class="dropdown-menu item">
              <li><a class="dropdown-item" href="#tuGrupo">Click aqui!</a></li>
            </ul>
          </li>
          <li class="nav-item dropdown item">
            <a
              class="nav-link dropdown-toggle"
              href="#"
              role="button"
              data-bs-toggle="dropdown"
              aria-expanded="false"
            >
            Donación 
            </a>
            <ul class="dropdown-menu item">
              <li>
                <a class="dropdown-item" href="#transfusion">Transfusión</a>
              </li>
              <li>
                <a class="dropdown-item" href="#donacion"
                  >Etapas de la donación</a
                >
              </li>
            </ul>
          </li>
          <li class="nav-item dropdown item">
            <a
              class="nav-link dropdown-toggle"
              href="#"
              role="button"
              data-bs-toggle="dropdown"
              aria-expanded="false"
            >
              Laboratorio
            </a>
            <ul class="dropdown-menu item">
              <li><a class="dropdown-item" href="#laboratorio">Galeria</a></li>
            </ul>
          </li>

          <li class="nav-item dropdown item">
            <a class="nav-link" href=""
              ><router-link to="/about">
                <strong> Requisitos Donación  </strong></router-link
              ></a
            >
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: "Menu",
};
</script>

<style scoped>
.navbar {
  position: fixed;
  width: 100%;
  background-color: rgb(255, 255, 255);
  font-family: "Open Sans", sans-serif;
}

a:link,
a:visited,
a:active {
  text-decoration: none;
  color: rgb(109, 107, 107);
}
</style>
