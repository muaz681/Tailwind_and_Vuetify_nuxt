<template>
  <div id="app">
    <Header />
    <Home />
    <Footer />
  </div>
</template>
<script>
import Header from "../components/frontend/Header.vue";
import Footer from "../components/frontend/Footer.vue";
import Home from "../components/frontend/Home.vue";
export default {
  components: { Header, Footer, Home },
};
</script>
