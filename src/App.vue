<template>
  <Header />
</template>

<script>
import Header from "./components/Header.vue";
export default {
  components: {
    Header,
  },
};
</script>

<style lang="scss">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

img {
  max-width: 100%;
  height: auto;
}

a {
  color: #596597;
  text-decoration: none;
}

body {
  min-height: 100vh;
}
</style>
