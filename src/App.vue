<template>
  <div class="container-fluid">
    <Navbar />
    <Home />
    <Footer />
  </div>
</template>

<script>
import Home from "@/components/home/Home.vue";
import Navbar from "@/components/Navbar.vue";
import Footer from "@/components/Footer.vue";

export default {
  components: {
    Home,
    Navbar,
    Footer
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
