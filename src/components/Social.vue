<template>
  <section id="social">
    <div class="container">
      <button>sign-up now!</button>
      <div>
        <span>follow us</span>
        <a href="#"><img src="@/assets/img/footer-facebook.png" alt="facebook"></a>
        <a href="#"><img src="@/assets/img/footer-twitter.png" alt="twitter"></a>
        <a href="#"><img src="@/assets/img/footer-youtube.png" alt="youtube"></a>
        <a href="#"><img src="@/assets/img/footer-pinterest.png" alt="pinterest"></a>
        <a href="#"><img src="@/assets/img/footer-periscope.png" alt="periscope"></a>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'Social',
}
</script>

<style scoped lang="scss">
  #social {
    height: 80px;
    background-color: #303030;
    .container {
      display: flex;
      justify-content: space-between;
      align-items: center;
      height: 100%;
      button {
        border: 2px solid #0282f9;
        padding: 8px;
        background-color: #303030;
        color: #fff;
        text-transform: uppercase;
        cursor: pointer;
      }
      div {
        height: 100%;
        display: flex;
        align-items: center;
        span {
          text-transform: uppercase;
          color: #0282f9;
          font-weight: bold;
        }
        img {
          padding-left: 15px;
        }
      }
    }
  }
</style>