<template>
  <slide />
  <imageCard />
  <arrivals header="Shoe Deals" />
  <products />
  <arrivals header="Shirt Deals" />
  <products />
  <arrivals header="Pants Deals" />
  <products />
  <second-slide />
</template>

<script>
import Slide from "@/components/home/subcomponents/Slide.vue";
import ImageCard from "@/components/home/subcomponents/ImageCard.vue";
import Arrivals from "@/components/home/subcomponents/Arrivals.vue";
import Products from "@/components/home/subcomponents/products.vue";
import SecondSlide from "@/components/home/subcomponents/secondSlide.vue";
// import axios from "axios";

export default {
  components: {
    Slide,
    ImageCard,
    Arrivals,
    Products,
    SecondSlide
  },
  data() {
    return {};
  }
};
</script>
