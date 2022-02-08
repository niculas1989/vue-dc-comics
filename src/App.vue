<template>
  <div>
    <Header />
    <Main />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Main from "./components/Main.vue";
export default {
  components: {
    Header,
    Main,
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
  background-color: #000;
  min-height: 100vh;
}

//! UTILITY
.container {
  margin: 0 auto;
  width: 1150px;
}
</style>
