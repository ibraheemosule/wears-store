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
import Slide from "./subcomponents/Slide.vue";
import ImageCard from "./subcomponents/ImageCard.vue";
import Arrivals from "./subcomponents/Arrivals.vue";
import Products from "./subcomponents/products.vue";
import SecondSlide from "./subcomponents/secondSlide.vue";

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
