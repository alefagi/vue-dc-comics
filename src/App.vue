<template>
  <div id="app">
    <Header />
    <main>
      <Content />
      <Shop />
    </main>
    <footer>
      <Links />
      <Social />
    </footer>
  </div>
</template>

<script>
import Header from '@/components/Header.vue';
import Content from '@/components/Content.vue';
import Shop from '@/components/Shop.vue';
import Links from '@/components/Links.vue';
import Social from '@/components/Social.vue';

export default {
  name: 'App',
  components: {
    Header,
    Content,
    Shop,
    Links,
    Social, 
  },
}
</script>

<style lang="scss">
@import "@/assets/scss/style.scss";
</style>
