<template>
  <Fragment>
    <app-header />
    <h1>{{ title }}</h1>
  </Fragment>
</template>

<script>
import { Fragment } from "vue-fragment";
import AppHeader from "./components/AppHeader.vue";

export default {
  components: {
    Fragment,
    AppHeader,
  },
  data: function () {
    return {
      title: "App",
    };
  },
};
</script>

<style></style>
