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
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.container {
  max-width: 1000px;
  margin: 0 auto;
}

img {
  max-width: 100%;
  max-height: 100%;
}
</style>
