<template>
  <div>
    <div id="upper-footer" class="container">
      <div>
        <div>
          <h4>DC COMICS</h4>
          <ul>
            <li><a href="#">Charatcters</a></li>
            <li><a href="#">Comics</a></li>
            <li><a href="#">Movies</a></li>
            <li><a href="#">TV</a></li>
            <li><a href="#">Games</a></li>
            <li><a href="#">Videos</a></li>
            <li><a href="#">News</a></li>
          </ul>
        </div>
        <div>
          <h4>SHOP</h4>
          <ul>
            <li><a href="#">Shop DC</a></li>
            <li><a href="#">Shop DC Collectibles</a></li>
          </ul>
        </div>
      </div>
      <div>
        <h4>DC</h4>
        <ul>
          <li><a href="#">Terme Of Use</a></li>
          <li><a href="#">Privacy policy (New)</a></li>
          <li><a href="#">Movies</a></li>
          <li><a href="#">Ad Choices</a></li>
          <li><a href="#">Advertising</a></li>
          <li><a href="#">Jobs</a></li>
          <li><a href="#">Talent Workshops</a></li>
          <li><a href="#">CPSC Certificates</a></li>
          <li><a href="#">Ratings</a></li>
          <li><a href="#">Shop Help</a></li>
          <li><a href="#">Contact Us</a></li>
        </ul>
      </div>
      <div>
        <h4>SITES</h4>
        <ul>
          <li><a href="#">DC</a></li>
          <li><a href="#">MAD Magazine</a></li>
          <li><a href="#">DC Kids</a></li>
          <li><a href="#">DC Universe</a></li>
          <li><a href="#">DC Pover Visa</a></li>
        </ul>
      </div>
    </div>

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

<style scoped lang="scss">
#upper-footer {
  height: 300px;
  background-image: url(../assets/img/footer-bg.jpg);
  display: flex;
  justify-content: flex-start;
  align-items: center;
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
h4 {
  color: white;
}

ul {
  display: flex;
  flex-direction: column;
  li {
    list-style: none;
    a {
      text-decoration: none;
    }
  }
}
</style>