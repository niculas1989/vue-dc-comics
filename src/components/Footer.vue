<template>
  <div>
    <div id="upper-footer" class="h-100">
      <section class="container">
        <div class="row mt-2">
          <div class="col-4">
            <div>
              <h6>DC COMICS</h6>
              <ul>
                <li v-for="link in firstLinks" :key="link.text">
                  <a href="#">{{ link.text }}</a>
                </li>
              </ul>
            </div>
            <div>
              <h6>SHOP</h6>
              <ul>
                <li v-for="link in secondLinks" :key="link.text">
                  <a href="#">{{ link.text }}</a>
                </li>
              </ul>
            </div>
          </div>
          <div class="col-4">
            <h6>DC</h6>
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
          <div class="col-4">
            <h6>SITES</h6>
            <ul>
              <li><a href="#">DC</a></li>
              <li><a href="#">MAD Magazine</a></li>
              <li><a href="#">DC Kids</a></li>
              <li><a href="#">DC Universe</a></li>
              <li><a href="#">DC Pover Visa</a></li>
            </ul>
          </div>
        </div>
      </section>
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
export default {
  data() {
    return {
      firstLinks: [
        { text: "Characters", url: "#", active: false },
        { text: "Movies", url: "#", active: true },
        { text: "Tv", url: "#", active: false },
        { text: "Games", url: "#", active: false },
        { text: "Collectibles", url: "#", active: false },
        { text: "Videos", url: "#", active: false },
        { text: "News", url: "#", active: false },
      ],
      secondLinks: [
        { text: "Shop DC", url: "#", active: false },
        { text: "Shop DC Collectibles", url: "#", active: true },
      ],
    };
  },
};
</script>

<style scoped lang="scss">
@import "../assets/sass/common.scss";
</style>