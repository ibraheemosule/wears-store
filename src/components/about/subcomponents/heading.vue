<template>
  <div class="container">
    <h2>
      {{ header }}
      <hr />
    </h2>
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
  margin-top: 5vmin;
  h2 {
    color: rgb(94, 1, 1);
    hr {
      border-width: 2px;
      width: 5%;
      color: rgba(31, 30, 30, 0.603);
      margin-left: 0;
    }
  }
}
</style>
