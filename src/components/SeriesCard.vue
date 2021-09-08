<template>
  <div class="card">
    <figure>
      <img :src="image" :alt="title">
    </figure>
    <figcaption>{{ title }}</figcaption>
  </div>
</template>

<script>
export default {
  name: 'SeriesCard',
  props: ['image', 'title'],
}
</script>

<style scoped lang="scss">
  .card {
    flex-basis: calc(100% / 6);
    padding-bottom: 40px;
  }

  figure {
    width: 160px;
    max-height: 160px;
    overflow: hidden;
    margin-bottom: 15px;
  }

  figcaption {
    text-transform: uppercase;
    font-size: 0.8rem;
    width: 160px;
  }
</style>