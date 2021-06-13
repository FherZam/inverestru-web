<template>
  <div class="container py-4 sm">
    <h1 class="text-center">Contáctanos</h1>
    <form
      @submit.prevent="enviarMensaje"
      class="container col-12 col-sm-12 col-md-6"
    >
      <div class="mb-3">
        <label for="inputNombre" class="form-label">Nombre</label>
        <input
          type="text"
          class="form-control"
          id="InputNombre"
          aria-describedby="emailHelp"
        />
      </div>
      <div class="mb-3">
        <label for="exampleInputEmail1" class="form-label">Email address</label>
        <input
          type="email"
          class="form-control"
          id="exampleInputEmail1"
          aria-describedby="emailHelp"
        />
        <div id="emailHelp" class="form-text">
          We'll never share your email with anyone else.
        </div>
      </div>
      <div class="">
        <label for="inputMensaje" class="form-label">Mensaje</label>
        <textarea
          class="form-control"
          placeholder="Deje su mensaje aquí"
          id="floatingTextarea2"
          style="height: 100px"
        ></textarea>
      </div>
      <button type="submit" class="btn btn-success mt-3">Enviar</button>
    </form>
    <div class="alert alert-success mt-3" role="alert" v-if="mostrarMsg">
      Mensaje enviado con éxito
    </div>
  </div>
</template>

<script>
export default {
  methods: {
    enviarMensaje() {
      this.mostrarMsg = true;
      setTimeout(this.ocultaMensaje, 2000);
    },
    ocultaMensaje() {
      this.mostrarMsg = false;
    },
  },
  data: () => ({
    mostrarMsg: false,
  }),
};
</script>
