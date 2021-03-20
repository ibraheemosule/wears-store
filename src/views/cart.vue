<template>
  <div class="container-fluid">
    <div class="row justify-content-center cart">
      <h1 class="col-sm-5">
        Cart
      </h1>
    </div>
    <div class="container">
      <cart-items />
    </div>
  </div>
</template>

<script>
import cartItems from "@/components/cart/cartItems.vue";
export default {
  components: {
    cartItems
  }
};
</script>

<style lang="scss" scoped>
.container-fluid {
  padding: 0;
  .cart {
    background-color: #cacaca77;
    margin: {
      left: 0;
      right: 0;
    }
    padding-top: 5vmin;
    padding-bottom: 5vmin;
    .col-sm-5 {
      text-align: center;
      padding: 5vh 0;
      color: rgb(94, 1, 1);
    }
  }
}
</style>
