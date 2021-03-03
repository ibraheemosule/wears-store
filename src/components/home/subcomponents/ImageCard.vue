<template>
  <div class="container-fluid">
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
  margin-top: 10vh;
  .card {
    border: none;
    padding: 0 15px;

    div.card-img-overlay {
      margin-top: 30%;
      text-align: center;
      color: rgba(255, 255, 255, 0.849);
    }
  }
}
</style>
