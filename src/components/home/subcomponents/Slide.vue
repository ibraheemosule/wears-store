<template>
  <div id="slider" class="carousel slide" data-ride="carousel">
    <!-- <ul class="carousel-indicators">
      <li data-target="#demo" data-slide-to="0" class="active"></li>
      <li data-target="#demo" data-slide-to="1"></li>
      <li data-target="#demo" data-slide-to="2"></li>
    </ul> -->
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img :src="require('@/assets/Images/one.jpg')" alt="Los Angeles" />
        <div class="carousel-caption">
          <h1>Los Angeles</h1>
          <h3>We had such a great time in LA!</h3>
        </div>
      </div>
      <div class="carousel-item">
        <img :src="require('@/assets/Images/two.jpg')" alt="Chicago" />
        <div class="carousel-caption">
          <h1>Chicago</h1>
          <h3>Thank you, Chicago!</h3>
        </div>
      </div>
      <div class="carousel-item">
        <img :src="require('@/assets/Images/three.jpg')" alt="New York" />
        <div class="carousel-caption">
          <h1>New York</h1>
          <h3>We love the Big Apple!</h3>
        </div>
      </div>
    </div>
    <a class="carousel-control-prev" href="#slider" data-slide="prev">
      <span class="carousel-control-prev-icon"></span>
    </a>
    <a class="carousel-control-next" href="#slider" data-slide="next">
      <span class="carousel-control-next-icon"></span>
    </a>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
div.carousel {
  margin-top: 5vh;
  margin: {
    right: 0;
    left: 0;
  }
  div.carousel-item {
    height: 600px;
    div.carousel-caption {
      color: rgb(94, 1, 1);
      top: 50vmin;
      h1 {
        font-size: 5vmax;
        font-weight: 900;
      }
      h3 {
        font-size: 2vmax;
        color: white;
      }
    }
    img {
      width: 100%;
      max-height: 100%;
      object-fit: cover;
    }
  }
}
</style>
