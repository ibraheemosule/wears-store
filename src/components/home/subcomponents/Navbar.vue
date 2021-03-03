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
            <a class="nav-link" href="#">Home</a>
          </li>
          <li class="nav-item mx-sm-3" key="about">
            <a class="nav-link" href="#">About</a>
          </li>
          <li class="nav-item mx-sm-3" key="shop">
            <a class="nav-link" href="#">Shop</a>
          </li>
          <li class="nav-item mx-sm-3" key="cart">
            <a class="nav-link" href="#">Cart</a>
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
