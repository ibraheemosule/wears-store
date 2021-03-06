<template>
  <div class="container-fluid">
    <div class="row justify-content-center">
      <div class="col-sm-5 img">
        <img :src="require('@/assets/Images/about.jpg')" alt="about us" />
      </div>
      <div class="col-sm-5 col-offset-2">
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris quis
          nisl ut lacus commodo posuere viverra in erat. Pellentesque volutpat
          eu felis in aliquet. Sed vehicula iaculis condimentum. Proin porta
          ligula eu consectetur blandit. Donec nec pharetra urna. Interdum et
          malesuada fames ac ante ipsum primis in faucibus. Aliquam lacus ipsum,
          elementum varius velit rutrum, tempor fermentum nibh. Praesent egestas
          massa dolor, sed hendrerit mi vulputate ac. Praesent eleifend ultrices
          augue. Morbi blandit diam nec consectetur finibus. Sed a lorem est.
          Pellentesque dictum vestibulum ullamcorper. Maecenas eget tempor ante,
          eleifend varius arcu. Suspendisse a mollis mauris.
        </p>
        <Arrivals header="Mission" />
        <p>
          Praesent eleifend ultrices augue. Morbi blandit diam nec consectetur
          finibus. Sed a lorem est. Pellentesque dictum vestibulum ullamcorper.
          Maecenas eget tempor ante, eleifend varius arcu. Suspendisse a mollis
          mauris.
        </p>
        <Arrivals header="Vision" />
        <p>
          Praesent eleifend ultrices augue. Morbi blandit diam nec consectetur
          finibus. Sed a lorem est. Pellentesque dictum vestibulum ullamcorper.
          Maecenas eget tempor ante, eleifend varius arcu. Suspendisse a mollis
          mauris.
        </p>
      </div>
    </div>
  </div>
</template>

<script>
import Arrivals from "./heading.vue";
export default {
  components: {
    Arrivals
  }
};
</script>

<style lang="scss" scoped>
.container-fluid {
  margin-top: 10vmin;
  .row {
    margin: {
      right: 0;
      left: 0;
    }
    align-items: center;
    .img {
      height: 60vmin;
    }
    .col-sm-5 {
      img {
        max-width: 100%;
        max-height: 100%;
      }
      p {
        margin-top: 3vmin;
      }
    }
  }
}
</style>
