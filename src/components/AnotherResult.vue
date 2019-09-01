<template>
  <div>
    <div>Counter is {{ doubleCounter }}</div>
    <div>Number of clicks: {{ stringCounter }}</div>
  </div>
</template>

<script>
import { mapGetters } from "vuex";
export default {
  computed: {
    ...mapGetters(["doubleCounter", "stringCounter"])
  }
  // counter() {
  //   return this.$store.getters.doubleCounter;
  // },
  // clicks() {
  //   return this.$store.getters.stringCounter;
  // }
};
</script>

<style>
</style>
