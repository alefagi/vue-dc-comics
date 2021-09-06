<template>
  <section id="shop">
    <div class="container">
      <a href="#">
        <figure>
          <img src="@/assets/img/buy-comics-digital-comics.png" alt="digital-comics">
        </figure>
        <span>digital comics</span>
      </a>
      <a href="#">
        <figure>
          <img src="@/assets/img/buy-comics-merchandise.png" alt="merchandise">
        </figure>
        <span>dc merchandise</span>
      </a>
      <a href="#">
        <figure>
          <img src="@/assets/img/buy-comics-subscriptions.png" alt="subscriptions">
        </figure>
        <span>subscription</span>
      </a>
      <a href="#">
        <figure>
          <img src="@/assets/img/buy-comics-shop-locator.png" alt="shop-locator">
        </figure>
        <span>comic shop locator</span>
      </a>
      <a href="#">
        <figure>
          <img src="@/assets/img/buy-dc-power-visa.svg" alt="buy-dc">
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
  #shop {
    height: 120px;
    background-color: #0282f9;
    .container {
      height: 100%;
      display: flex;
      justify-content: space-evenly;
      align-items: center;
      a {
        height: 100%;
        display: flex;
        align-items: center;
        text-decoration: none;
        span {
          color: #fff;
          text-transform: uppercase;
          font-size: 0.8rem;
          padding-left: 5px;
        }
        figure {
          height: 50px;
          width: 50px;
          display: flex;
        }
      }
    }
  }
</style>