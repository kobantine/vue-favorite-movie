<template>
  <v-app>
    <Header />
    <v-content>
      <router-view />
    </v-content>
    <Footer />
  </v-app>
</template>

<script>
import Header from "./components/Header";
import Footer from "./components/Footer";
export default {
  components: { Header, Footer }
};
</script>
