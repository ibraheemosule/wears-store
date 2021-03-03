<template>
  <div class="container-fluid">
    <div class="row">
      <div class="card col-xs-6 col-sm-3">
        <img
          class="card-img-top"
          :src="require('@/assets/Images/six.jpg')"
          alt="Card image"
        />
        <span class="cart">this is one</span>
        <div class="card-body">
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
        <span class="cart">this is one</span>
        <div class="card-body">
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
        <span class="cart">this is one</span>
        <div class="card-body">
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
        <span class="cart">this is one</span>
        <div class="card-body">
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
  text-align: center;
  .card {
    border: none;
    padding: 0 15px;
    position: relative;

    div.card-body {
      text-align: center;
      color: rgba(41, 40, 40, 0.849);
      background-color: rgba(187, 187, 187, 0.452);
      transition: box-shadow 0.7s ease-out;
    }
    .card-body:hover {
      box-shadow: 0 0 2px 0 black;
    }
    .cart {
      position: absolute;
      right: 5%;
      top: 5%;
    }
  }
}
</style>
