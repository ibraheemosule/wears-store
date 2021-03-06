<template>
  <div class="container-fluid">
    <div class="row justify-content-center align-content-center">
      <h1 class="col-sm-5">
        About Us
      </h1>
    </div>
    <pngImage />
  </div>
</template>

<script>
import pngImage from "./subcomponents/pngImage.vue";
export default {
  components: {
    pngImage
  }
};
</script>

<style lang="scss" scoped>
.container-fluid {
  padding: 0;
  .row {
    background-color: rgba(202, 202, 202, 0.466);
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
