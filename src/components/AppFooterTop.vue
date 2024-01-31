<script>
export default {
  name: "AppFooterTop",
};
</script>

<template>
  <footer>
    <div class="footer-top">
      <div class="container">
        <img src="/src/assets/img/dc-logo-bg.png" alt="logo-big" />
        <div class="row d-flex">
          <div class="col-custom">
            <ul>
              <h2>DC Comics</h2>
              <li><a href="#">Characters</a></li>
              <li><a href="#">Comics</a></li>
              <li><a href="#">Movies</a></li>
              <li><a href="#">TV</a></li>
              <li><a href="#">Games</a></li>
              <li><a href="#">Videos</a></li>
              <li><a href="#">News</a></li>
            </ul>
            <ul>
              <h2>Shop</h2>
              <li><a href="#">Shop DC</a></li>
              <li><a href="#">Shop collectibles</a></li>
            </ul>
          </div>

          <div class="col-custom">
            <ul>
              <h2>DC</h2>
              <li><a href="#">Terms Of Use</a></li>
              <li><a href="#">Privacy policy (New)</a></li>
              <li><a href="#">Ad Choices</a></li>
              <li><a href="#">Advertising</a></li>
              <li><a href="#">Jobs</a></li>
              <li><a href="#">Videos</a></li>
              <li><a href="#">Talent Workshops</a></li>
              <li><a href="#">CPSC Certificates</a></li>
              <li><a href="#">Ratings</a></li>
              <li><a href="#">Shop help</a></li>
              <li><a href="#">Contact us</a></li>
            </ul>
          </div>

          <div class="col-custom">
            <ul>
              <h2>Sites</h2>
              <li><a href="#">DC</a></li>
              <li><a href="#">Mad Magazine</a></li>
              <li><a href="#">DC Kids</a></li>
              <li><a href="#">DC Universe</a></li>
              <li><a href="#">Jobs</a></li>
              <li><a href="#">DC Power Visa</a></li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<style scoped>
.footer-top {
  background-image: url("/src/assets/img/footer-bg.jpg");
}

.container {
  padding-top: 45px;
  padding-bottom: 60px;
  position: relative;
}

img {
  position: absolute;
  top: 50%;
  right: 0;
  transform: translateY(-50%);
}

.col-custom {
  width: calc(100% / 7);
}

ul {
  margin-bottom: 26px;
}

h2 {
  color: var(--dc-comics-light);
  text-transform: uppercase;
  margin-bottom: 22px;
}

a {
  color: var(--dc-comics-grey);
  line-height: 1.5;
}
</style>
