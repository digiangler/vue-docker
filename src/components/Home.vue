<template>
  <div class="container">
    <img :src="vueImg" alt="vueImg" class="vueImg" />
    <h1 class="title">{{ msg }}</h1>
    <img :src="dockerImg" alt="dockerImg" class="dockerImg" />
  </div>
</template>

<script>
import "./Home.css";
import vueImg from "../assets/vue.png";
import dockerImg from "../assets/docker.png";

export default {
  name: "Home",
  props: {
    msg: String,
  },
  data: () => {
    return {
      vueImg,
      dockerImg,
    };
  },
};
</script>
