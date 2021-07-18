<script>
export default {
  methods: {
    handTokentest () {
      this.$store.dispatch("HandToken", {
        token: ""
      });
    }
  }
};
</script>
<template>
  <button @click="handTokentest">TEST</button>
</template>

<style></style>
