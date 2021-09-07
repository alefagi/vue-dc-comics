<template>
  <section id="content">
    <div class="container">
      <h2>&#10511; Content goes here &#10510;</h2>
    </div>
  </section>
</template>

<script>
export default {
  name: 'Content',
}
</script>

<style scoped lang="scss">
@import "@/assets/scss/_variables.scss";

  #content {
    background-color: #1c1c1c;
    color: $brand-text;
    line-height: calc(100vh - 520px);
    height: calc(100vh - 520px);
  }
</style>