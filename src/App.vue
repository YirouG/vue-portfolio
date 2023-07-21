<template>
  <div id="app">
    <Navbar msg="Welcome to my portfolio" />
    <Jumbotron />
    <Gallery />
    <!-- <About /> -->
    <Contact />
    <Footer />
  </div>
</template>

<script>
import Navbar from "./components/Navbar.vue";
import Jumbotron from "./components/Jumbotron.vue";
import Gallery from "./components/Gallery.vue";
// import About from "./components/About.vue";
import Contact from "./components/Contact.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "App",
  components: {
    Navbar,
    Jumbotron,
    Gallery,
    // About,
    Contact,
    Footer,
  },
};
</script>

<style scoped></style>
