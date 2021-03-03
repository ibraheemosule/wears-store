<template>
  <div class="container">
    <h1>
      {{ header }}
      <hr />
    </h1>
  </div>
</template>

<script>
export default {
  props: {
    header: String
  }
};
</script>
s
<style lang="scss" scoped>
.container {
  margin-top: 10vh;
  h1 {
    text-align: center;
    color: rgb(94, 1, 1);
    hr {
      border-width: 2px;
      width: 5%;
      color: rgba(31, 30, 30, 0.603);
    }
  }
}
</style>
