<template>
  <div class="layout">
    <header class="header">
      <g-image src="~/assets/logoBB.png" width="200" />

      <nav class="nav">
        <g-link class="nav__link" to="/">Inicio</g-link>
        <g-link class="nav__link" to="/">Personas</g-link>
        <g-link class="nav__link" to="/">Empresas</g-link>
      </nav>
      <span class="button-login">Iniciar sesión</span>
    </header>
    <slot />
  </div>
</template>

<static-query>
query {
  metadata {
    siteName
  }
}
</static-query>

<style>
body {
  font-family: -apple-system, system-ui, BlinkMacSystemFont, "Segoe UI", Roboto,
    "Helvetica Neue", Arial, sans-serif;
  margin: 0;
  padding: 0;
  line-height: 1.5;
}

.layout {
  max-width: 960px;
  margin: 0 auto;
  padding-left: 20px;
  padding-right: 20px;
}

.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 20px;
  height: 80px;
}

.button-login {
  background-color: #3298dc;
  color: white;
  font-weight: bold;
  padding: 0.5rem;
  border-radius: 5px;
}

.nav__link {
  margin-left: 20px;
  text-decoration: none;
  color: black;
}

.left,
.right {
  width: 50%;
  display: inline-block;
}
</style>
