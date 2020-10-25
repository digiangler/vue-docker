<template>
  <div id="app">
    <Home msg="I LOVE VUE & DOCKER" />
  </div>
</template>

<script>
import Home from "./components/Home.vue";

export default {
  name: "App",
  components: {
    Home,
  },
};
</script>
