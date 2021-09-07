<template>
  <section id="links">
    <div class="container">
      <div class="list">
        <div>
          <h4>dc comics</h4>
          <ul>
            <li><a href="#">Characters</a></li>
            <li><a href="#">Comics</a></li>
            <li><a href="#">Movies</a></li>
            <li><a href="#">TV</a></li>
            <li><a href="#">Games</a></li>
            <li><a href="#">Videos</a></li>
            <li><a href="#">News</a></li>
          </ul>
          <h4>shop</h4>
          <ul>
            <li><a href="#">Shop DC</a></li>
            <li><a href="#">Shop DC Collectibles</a></li>
          </ul>
        </div>
        <div>
          <h4>dc</h4>
          <ul>
            <li><a href="#">Terms Of Use</a></li>
            <li><a href="#">Privacy Policy (New)</a></li>
            <li><a href="#">Ad Choices</a></li>
            <li><a href="#">Advertising</a></li>
            <li><a href="#">Jobs</a></li>
            <li><a href="#">Subscriptions</a></li>
            <li><a href="#">Talent Workshops</a></li>
            <li><a href="#">CPSC Certificates</a></li>
            <li><a href="#">Ratings</a></li>
            <li><a href="#">Shop Help</a></li>
            <li><a href="#">Contact Us</a></li>
          </ul>
        </div>
        <div>
          <h4>sites</h4>
          <ul>
            <li><a href="#">DC</a></li>
            <li><a href="#">MAD Magazine</a></li>
            <li><a href="#">DC Kids</a></li>
            <li><a href="#">DC Universe</a></li>
            <li><a href="#">DC Power Visa</a></li>
          </ul>
        </div>
      </div>
      <figure>
        <img src="@/assets/img/dc-logo-bg.png" alt="logo-bg">
      </figure>
    </div>
  </section>
</template>

<script>
export default {
  name: 'Links',
}
</script>

<style scoped lang="scss">
@import "@/assets/scss/_variables.scss";

  #links {
    background-image: url('../assets/img/footer-bg.jpg');
    background-size: cover;
    height: 270px;
    .container {
      display: flex;
      justify-content: space-between;
    }
  }

  .list {
    display: flex;
    padding-top: 30px;
    &>div {
      padding-right: 30px;
    }
  }

  h4 {
    color: $brand-text;
    text-transform: uppercase;
    margin-bottom: 10px;
    margin-top: 10px;
  }

  li {
    list-style-type: none;
    font-size: 0.8rem;
    a {
      text-decoration: none;
      color: gray;
    }
  }

  figure {
    height: 270px;
    width: 410px;
    position: relative;
    overflow: hidden;
    img {
      max-height: 410px;
      max-width: 410px;
      position: absolute;
      top: -70px;
    }
  }
</style>