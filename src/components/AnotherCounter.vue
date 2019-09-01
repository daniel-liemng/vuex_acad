<template>
  <div>
    <button @click="asyncIncrement({ by: 100, duration: 5000})">Another Increment</button>
    <button @click="asyncDecrement({ by: 50, duration: 5000})">Another Decrement</button>
  </div>
</template>

<script>
import { mapActions } from "vuex";
export default {
  methods: {
    ...mapActions(["asyncIncrement", "asyncDecrement"])
    // increment() {
    //   this.$store.commit("increment");
    // },
    // decrement() {
    //   this.$store.commit("decrement");
    // }
  }
};
</script>

<style>
</style>
