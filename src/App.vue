<template>
  <div id="nav" class="back">
    <Header />

    <router-view />

    <div class="footer">
      <footer class="my-3 text-center text-white  bg-success bg-gradient">
        <h4>&copy; {{ getYear }} - Inverestru</h4>
        <p>
          Av. de Los Insurgentes 2604 Col. Los Alamos CP. 36555 Irapuato,
          Gto.<br />
          Teléfono (462) 6 23 73 51
        </p>
      </footer>
    </div>
  </div>
</template>

<script>
import Header from "./components/Header.vue";
//import Footer from "./components/Footer.vue";

export default {
  components: {
    Header,
  //  Footer,
  },
  computed: {
    getYear() {
      return new Date().getFullYear();
    },
  },
};
</script>
