<template>
  <div class="nav">
    <div class="logo__container">
      <p>88:88</p>
    </div>
    <div class="menu__container">
      <div class="menu__interactive">
        <ul class="list_menu">
          <li><a href="#">Servicios</a></li>
          <li><a href="#">Nosotros</a></li>
          <li><a href="#">Contacto</a></li>
        </ul>
      </div>
      <div class="menu__another">
        <ul class="list_menu">
          <li><a href="htt#">Faqs</a></li>
          <li><a href="#">Suscribirse</a></li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Nav",
};
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Major+Mono+Display&display=swap");
.nav {
  background-color: #fafbfc;
  display: flex;
  flex-direction: row;
  align-items: center;
  padding: 0 2%;
}
.logo__container {
  width: 20%;
  font-family: "Major Mono Display", monospace;
  font-size: 2rem;
}
.menu__container {
  min-height: 10vh;
  width: 80%;
  display: flex;
  flex-direction: row;
  align-items: center;
}
.menu__interactive {
  width: 70%;
  display: flex;
  justify-content: flex-end;
}
.menu__another {
  width: 30%;
  display: flex;
  justify-content: flex-end;
}

@media only screen and (max-width: 575px) {
  .nav {
    flex-direction: column;
  }

  .logo__container {
    display: flex;
    justify-content: center;
    width: 100%;
    font-family: "Major Mono Display", monospace;
    font-size: 2rem;
    margin: 10px 0;
  }
  .menu__container {
    min-height: 10vh;
    width: 100%;
    display: flex;
    flex-direction: column;
    align-items: center;
  }
  .menu__interactive {
    width: 100%;
    display: flex;
    margin: 10px 0;
  }
  .menu__another {
    width: 100%;
    display: flex;
    justify-content: center;
  }
}
</style>