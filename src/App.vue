<template>
  <div>
    <Header />
    <Main />
    <Footer />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Main from "./components/Main.vue";
import Footer from "./components/Footer.vue";
export default {
  components: {
    Header,
    Main,
    Footer,
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

.main-color {
  color: #0082f9;
}

.main-text {
  color: #5a646b;
}
</style>
