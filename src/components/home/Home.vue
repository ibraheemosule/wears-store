<template>
  <Navbar />
  <Slide />
  <ImageCard />
  <Arrivals />
  <Products />
  <Footer />
</template>

<script>
import Navbar from "./subcomponents/Navbar.vue";
import Slide from "./subcomponents/Slide.vue";
import ImageCard from "./subcomponents/ImageCard.vue";
import Arrivals from "./subcomponents/Arrivals.vue";
import Products from "./subcomponents/products.vue";
import Footer from "./subcomponents/Footer.vue";

export default {
  components: {
    Navbar,
    Slide,
    ImageCard,
    Arrivals,
    Products,
    Footer
  },
  data() {
    return {};
  }
};
</script>

<style></style>
