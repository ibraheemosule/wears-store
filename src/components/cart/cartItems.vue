<template>
  <div class="row">
    <div class="col-sm-2">
      <table>
        <thead>
          <h5>Delete</h5>
        </thead>
      </table>
    </div>
    <div class="col-sm-2">
      <table>
        <thead>
          <h5>Image</h5>
        </thead>
      </table>
    </div>
    <div class="col-sm-2">
      <table>
        <thead>
          <h5>Name</h5>
        </thead>
      </table>
    </div>
    <div class="col-sm-2">
      <table>
        <thead>
          <h5>Price</h5>
        </thead>
      </table>
    </div>
    <div class="col-sm-2">
      <table>
        <thead>
          <h5>Quantity</h5>
        </thead>
        <tbody>
          <div class="quantity">
            <button class="btn btn-primary"><sup>_</sup></button>
            <span> 1 </span>
            <button class="btn btn-primary">+</button>
          </div>
        </tbody>
      </table>
    </div>
    <div class="col-sm-2">
      <table>
        <thead>
          <h5>Total</h5>
        </thead>
        <tbody></tbody>
      </table>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.row {
  margin-top: 5vmin;
  justify-content: space-around;
  text-align: center;
  .col-sm-2 {
    border: 2px #cacaca77 solid;
    h5 {
      color: rgb(94, 1, 1);
      text-align: center;
    }
    .quantity {
      border: 1px #cacaca77 solid;
      border-radius: 8px;
    }
  }
}
</style>
