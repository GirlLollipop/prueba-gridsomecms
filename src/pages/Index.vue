<template>
  <Layout>
    <!-- Learn how to use images here: https://gridsome.org/docs/images -->
    <section class="top">
      <div class="left">
        <h1>Llegó la era de la Transformación Broxel 5.0; ya nada será igual.</h1>
        <p>
          No te quedes fuera de la Transformación que marcará un antes y un después en medios de
          pago. Regístrate con tu Email en 5 segundos en esta lista de espera y gana dinero al invitar
          a más personas.
        </p>
        <form>
          <div class="right">
            <input type="text" placeholder="Ingresa tu Email" />
          </div>
          <div class="left">
            <button class="cta" type="submit">Únete ahora</button>
          </div>
        </form>
      </div>
      <div class="right">
        <g-image src="~/assets/wl2-1.png" width="400" />
      </div>
    </section>
    <section class="middle">
      <div class="left">
        <h1>Sé de los primeros usuarios privilegiados en Transformar el dinero en algo “más valioso”.</h1>
        <p>
          Cada vez que invitas a alguien a nuestra
          Transformación buenas cosas pasan, por ejemplo, tienes acceso a meses gratis en Netflix, Spotify o Amazon Prime.
        </p>
        <p>
          <strong>Uno, tres y doce meses gratis de tu plataforma favorita.</strong>
        </p>
        <g-image src="~/assets/icon.png" width="200" />
      </div>
      <div class="left">
        <g-image class="video" src="~/assets/video.png" width="400" />
      </div>
    </section>
    <footer>
      <p>
        <small>
          Broxel by Broxel. The source code is licensed.
          <br />2020
        </small>
      </p>
    </footer>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: "Hello, world!"
  }
};
</script>

<style>
.home-links a {
  margin-right: 1rem;
}

p,
h1,
form {
  padding: 20px;
}

footer {
  text-align: center;
}

.video {
  float: right;
  margin: 20px;
  margin-bottom: 40%;
}
.middle {
  background-color: #f5f5f5;
  width: 100% !important;
  margin: 0 !important;
  max-width: 100% !important;
}
.cta {
  background-color: #3298dc;
  color: white;
  font-weight: bold;
  padding: 0.5rem;
  border-radius: 5px;
  border: none;
}
</style>
