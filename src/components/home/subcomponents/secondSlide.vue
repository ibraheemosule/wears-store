<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col-sm-4">
        <h1>
          Shop With Us
          <hr />
        </h1>
        <h3>Free Nationwide Delivery</h3>
        <p>
          We deliver your products to your doorsteps within the shortest amount
          of time
        </p>
        <button class="btn btn-primary">CLICK HERE</button>
      </div>
      <img
        class="card-img-top"
        :src="require('@/assets/Images/six.jpg')"
        alt="Card image"
      />
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.container-fluid {
  margin-top: 10vh;
  .row {
    position: relative;
    height: 500px;
    justify-content: flex-end;
    align-items: center;
    img {
      position: absolute;
      max-width: 100%;
      max-height: 100%;
      object-position: top;
      object-fit: cover;
      z-index: 0;
    }
    .col-sm-4 {
      z-index: 1;
      margin-right: 7vw;
      color: rgb(94, 1, 1);
      h1 {
        hr {
          border-width: 2px;
          width: 20%;
          color: rgba(31, 30, 30, 0.603);
          margin-left: 0;
        }
      }
      p {
        // color: white;
        margin-top: 5vh;
      }
    }
  }
}
</style>
