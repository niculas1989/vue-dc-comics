<template>
  <header class="container">
    <figure>
      <img src="../assets/img/dc-logo.png" alt="" />
    </figure>
    <ul>
      <li><a href="#">Characters</a></li>
      <li><a href="#">COMICS</a></li>
      <li><a href="#">MOVIES</a></li>
      <li><a href="#">TV</a></li>
      <li><a href="#">GAMES</a></li>
      <li><a href="#">COLLECTIBLES</a></li>
      <li><a href="#">VIDEOS</a></li>
      <li><a href="#">FANS</a></li>
      <li><a href="#">NEWS</a></li>
      <li><a href="#">SHOP</a></li>
    </ul>
  </header>
</template>

<script>
export default {};
</script>

<style lang="scss">
header {
  display: flex;
  justify-content: space-between;
}

ul {
  li {
    display: inline-block;
    a {
      margin: 0 10px;
    }
  }
}
</style>
