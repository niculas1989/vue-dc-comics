<template>
  <header>
    <div class="container">
      <div id="nav">
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
      </div>
    </div>
  </header>
</template>

<script>
export default {};
</script>

<style lang="scss">
header {
  background-color: white;
}

#nav {
  margin-top: 40px;
  display: flex;
  justify-content: space-between;
  align-items: center;
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
