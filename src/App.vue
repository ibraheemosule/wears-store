<template>
  <div class="container-fluid">
    <Navbar />
    <!-- <Home /> -->
    <!-- <about /> -->
    <cart />
    <Footer />
  </div>
</template>

<script>
// import Home from "@/components/home/Home.vue";
import Navbar from "@/components/Navbar.vue";
import Footer from "@/components/Footer.vue";
// import about from "@/components/about/about.vue";
import cart from "@/components/cart/cart.vue";

export default {
  components: {
    // Home,
    Navbar,
    Footer,
    // about,
    cart
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
