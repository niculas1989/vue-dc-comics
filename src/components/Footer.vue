<template>
  <div>
    <div id="upper-footer"></div>
    <div id="bottom-footer">
      <div class="container">
        <div class="wrapper">
          <span id="button"><a href="#">SIGN UP NOW</a></span>
          <div>
            <span class="main-color">FOLLOW US:</span>
            <img src="../assets/img/footer-facebook.png" alt="Facebook" />
            <img src="../assets/img/footer-twitter.png" alt="Twitter" />
            <img src="../assets/img/footer-youtube.png" alt="Youtube" />
            <img src="../assets/img/footer-pinterest.png" alt="Pinterest" />
            <img src="../assets/img/footer-periscope.png" alt="Periscope" />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
#upper-footer {
  height: 300px;
  background-image: url(../assets/img/footer-bg.jpg);
}

#bottom-footer {
  height: 100px;
  background-color: #303030;
  .wrapper {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
}

img {
  height: 20px;
  padding: 0 10px;
}
</style>