<template>
  <div>
    <nav class="navbar navbar-expand-md">
      <a class="navbar-brand mr-sm-5" href="#">Logo</a>
      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#nav"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="nav">
        <ul class="navbar-nav">
          <li class="nav-item mx-sm-3" key="home">
            <router-link to="/" class="nav-link">Home</router-link>
          </li>
          <li class="nav-item mx-sm-3" key="about">
            <router-link to="/about" class="nav-link">About</router-link>
          </li>
          <li class="nav-item mx-sm-3" key="shop">
            <router-link to="/shop" class="nav-link">Shop</router-link>
          </li>
          <li class="nav-item mx-sm-3" key="cart">
            <router-link to="/cart" class="nav-link">Cart</router-link>
          </li>
          <li class="nav-item mx-sm-3" key="contact">
            <a class="nav-link" href="#">Contact</a>
          </li>
        </ul>
      </div>
    </nav>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.navbar {
  background: transparent;
  span {
    background-color: black;
  }
  a {
    color: hsl(120, 2%, 9%);
  }
  a:hover {
    color: hsla(120, 2%, 18%, 0.267);
  }
}
</style>
