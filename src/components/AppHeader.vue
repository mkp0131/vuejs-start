<template>
  <header>
    <h1>Header</h1>
    <app-nav v-bind:title="title" />
  </header>
</template>

<script>
import AppNav from "./AppNav.vue";
export default {
  components: {
    AppNav,
  },
  data: function () {
    return {
      title: "good",
    };
  },
};
</script>

<style></style>
