<template>
  <div>
    <button @click="increment(4)">Increment</button>
    <button @click="decrement(20)">Decrement</button>
  </div>
</template>

<script>
import { mapActions } from "vuex";
export default {
  methods: {
    ...mapActions(["increment", "decrement"])
  }

  // methods: {
  //   increment() {
  //     this.$store.state.counter++;
  //   },
  //   decrement() {
  //     this.$store.state.counter--;
  //   }
  // }
};
</script>

<style>
</style>
