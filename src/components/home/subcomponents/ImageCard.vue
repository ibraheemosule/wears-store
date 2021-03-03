<template>
  <div class="container-fluid">
    <div class="row justify-content-center align-content-center">
      <h1 class="col-sm-5">
        We Have The Best Wears For Every Occasion Ranging From Shirts, Pants,
        Caps etc.
      </h1>
    </div>
    <div class="row">
      <div class="card col-xs-6 col-sm-3">
        <img
          class="card-img-top"
          :src="require('@/assets/Images/six.jpg')"
          alt="Card image"
        />
        <div class="card-img-overlay">
          <h4 class="card-title">John Doe</h4>
          <p class="card-text">Some example text.</p>
          <a href="#" class="btn btn-primary">See Profile</a>
        </div>
      </div>
      <div class="card col-xs-6 col-sm-3">
        <img
          class="card-img-top"
          :src="require('@/assets/Images/six.jpg')"
          alt="Card image"
        />
        <div class="card-img-overlay">
          <h4 class="card-title">John Doe</h4>
          <p class="card-text">Some example text.</p>
          <a href="#" class="btn btn-primary">See Profile</a>
        </div>
      </div>
      <div class="card col-xs-6 col-sm-3">
        <img
          class="card-img-top"
          :src="require('@/assets/Images/six.jpg')"
          alt="Card image"
        />
        <div class="card-img-overlay">
          <h4 class="card-title">John Doe</h4>
          <p class="card-text">Some example text.</p>
          <a href="#" class="btn btn-primary">See Profile</a>
        </div>
      </div>
      <div class="card col-xs-6 col-sm-3">
        <img
          class="card-img-top"
          :src="require('@/assets/Images/six.jpg')"
          alt="Card image"
        />
        <div class="card-img-overlay">
          <h4 class="card-title">John Doe</h4>
          <p class="card-text">Some example text.</p>
          <a href="#" class="btn btn-primary">See Profile</a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.container-fluid {
  .row {
    background-color: rgba(202, 202, 202, 0.466);
    .col-sm-5 {
      text-align: center;
      padding: 5vh 0;
      color: rgb(94, 1, 1);
    }
  }
  .card {
    border: none;
    padding: 0 15%;

    div.card-img-overlay {
      margin-top: 30%;
      text-align: center;
      color: rgba(255, 255, 255, 0.849);
    }
  }
}
</style>
