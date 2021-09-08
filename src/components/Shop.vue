<template>
  <section id="shop">
    <div class="container">
      <a href="#">
        <figure>
          <img src="../assets/img/buy-comics-digital-comics.png" alt="digital-comics">
        </figure>
        <span>digital comics</span>
      </a>
      <a href="#">
        <figure>
          <img src="../assets/img/buy-comics-merchandise.png" alt="merchandise">
        </figure>
        <span>dc merchandise</span>
      </a>
      <a href="#">
        <figure>
          <img src="../assets/img/buy-comics-subscriptions.png" alt="subscriptions">
        </figure>
        <span>subscription</span>
      </a>
      <a href="#">
        <figure>
          <img src="../assets/img/buy-comics-shop-locator.png" alt="shop-locator">
        </figure>
        <span>comic shop locator</span>
      </a>
      <a href="#">
        <figure>
          <img src="../assets/img/buy-dc-power-visa.svg" alt="buy-dc">
        </figure>
        <span>dc power visa</span>
      </a>
    </div>
  </section>
</template>

<script>
export default {
  name: 'Shop',
}
</script>

<style scoped lang="scss">
@import "../assets/scss/_variables.scss";

  #shop {
    height: 100px;
    background-color: $brand-primary;
    .container {
      height: 100%;
      display: flex;
      justify-content: space-evenly;
      align-items: center;
    }
  }

  a {
    height: 100%;
    display: flex;
    align-items: center;
    text-decoration: none;
    figure {
      height: 40px;
      width: 40px;
      display: flex;
    }
    span {
      color: $brand-text;
      text-transform: uppercase;
      font-size: 0.8rem;
      padding-left: 5px;
    }
  }
</style>