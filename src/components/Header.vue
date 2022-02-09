<template>
  <header>
    <div class="container">
      <div id="nav">
        <figure>
          <img src="../assets/img/dc-logo.png" alt="" />
        </figure>
        <ul>
          <li v-for="link in links" :key="link.text">
            <a href="link.url">{{ link.text }}</a>
          </li>
        </ul>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  data() {
    return {
      links: [
        { text: "Characters", url: "#", active: false },
        { text: "Movies", url: "#", active: true },
        { text: "Tv", url: "#", active: false },
        { text: "Games", url: "#", active: false },
        { text: "Collectibles", url: "#", active: false },
        { text: "Videos", url: "#", active: false },
        { text: "Fans", url: "#", active: false },
        { text: "News", url: "#", active: false },
        { text: "Shop", url: "#", active: false },
      ],
    };
  },
};
</script>

<style scoped lang="scss">
@import "../assets/sass/_header.scss";
</style>
