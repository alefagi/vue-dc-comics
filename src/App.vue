<template>
  <div id="app">
    <Header />
    <main>
      <Jumbotron />
      <CurrentSeries />
      <Shop />
    </main>
    <footer>
      <Links />
      <Social />
    </footer>
  </div>
</template>

<script>
import Header from './components/Header.vue';
import CurrentSeries from './components/CurrentSeries.vue';
import Shop from './components/Shop.vue';
import Links from './components/Links.vue';
import Social from './components/Social.vue';
import Jumbotron from './components/Jumbotron.vue';

export default {
  name: 'App',
  components: {
    Header,
    Jumbotron,
    CurrentSeries,
    Shop,
    Links,
    Social, 
  },
}
</script>

<style lang="scss">
@import "./assets/scss/style.scss";
</style>
