<template>
  <div class="container-fluid">
    <div>
      <Navbar />
      <!-- <Home /> -->
      <!-- <about />
    <cart /> -->
    </div>
    <router-view />
    <Footer />
  </div>
</template>

<script>
// import Home from "@/views/Home.vue";
import Navbar from "@/components/Navbar.vue";
import Footer from "@/components/Footer.vue";
// import about from "@/views/About.vue";
// import cart from "@/views/cart.vue";

export default {
  components: {
    // Home,
    Navbar,
    Footer
    // about,
    // cart
  },
  data() {
    return {};
  }
};
</script>

<style lang="scss" scoped>
.container-fluid {
  padding: 0;
}
</style>
