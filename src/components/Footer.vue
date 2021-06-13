<template>
  <div class="footer">
    <footer class="text-center bg-dark text-white  bg-gradient">
      <h4>&copy; {{ getYear }} - Inverestru</h4>
      <p>
        Av. de Los Insurgentes 2604 Col. Los Alamos CP. 36555 Irapuato, Gto.<br />
        Teléfono (462) 6 23 73 51
      </p>
    </footer>
  </div>
</template>

<script>
export default {
  data: () => ({}),
  computed: {
    getYear() {
      return new Date().getFullYear();
    },
  },
};
</script>

<style>
.footer {
  position: fixed;
  bottom: 0;
  width: 100%;
}
</style>
