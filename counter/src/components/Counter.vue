<template>
  <div class="hello">
    <h1>Counter App</h1>
    <span>{{ count }}</span>
    <div class="btns">
      <button @click="increment">Increment</button>
      <button @click="decrement">Decrement</button>
      <button @click="reset">Reset</button>
    </div>
  </div>
</template>

<script>
export default {
  name: "Counter",
  data() {
    return { count: 0 };
  },
  methods: {
    increment() {
      console.log("working", this.count + 1);
      this.count + 1;
    },
    decrement() {
      this.count - 1;
    },
    reset() {
      this.count = 0;
    },
  },
};
</script>

<style scoped>
span {
  font-size: 48px;
  font-weight: bold;
}
.btns {
  display: flex;
  justify-content: center;
}
button {
  margin: 0 4px;
  border: none;
  padding: 8px 32px;
  background-color: aquamarine;
  border-radius: 4px;
  cursor: pointer;
}
</style>
