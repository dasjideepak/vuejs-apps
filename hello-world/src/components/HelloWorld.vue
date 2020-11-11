<template>
  <div class="hello">
    <h1>Welcome to VueJS App</h1>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.hello {
  padding: 12px 40px;
  border: 1px solid black;
}
h1 {
  font-size: 40px;
  text-align: center;
}
</style>
