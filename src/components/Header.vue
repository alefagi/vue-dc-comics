<template>
  <header class="container">
    <figure>
      <img src="../assets/img/dc-logo.png" alt="dc-logo">
    </figure>
    <nav>
      <ul>
        <li v-for="(item, index) in links" :key="index"><a href="#" :class="{active: item.current}">{{ item.text }}</a></li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {
  name: 'Header',
  data() {
    return {
      links: [
        {
          text: 'Characters',
          url: '#',
          current: false,
        },
        {
          text: 'Comics',
          url: '#',
          current: true,
        },
        {
          text: 'Movies',
          url: '#',
          current: false,
        },
        {
          text: 'TV',
          url: '#',
          current: false,
        },
        {
          text: 'Games',
          url: '#',
          current: false,
        },
        {
          text: 'Collectibles',
          url: '#',
          current: false,
        },
        {
          text: 'Videos',
          url: '#',
          current: false,
        },
        {
          text: 'Fans',
          url: '#',
          current: false,
        },
        {
          text: 'News',
          url: '#',
          current: false,
        },
        {
          text: 'Shop',
          url: '#',
          current: false,
        },
      ],
    }
  }
}
</script>

<style scoped lang="scss">
@import "../assets/scss/_variables.scss";

  header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    height: 80px;
    figure {
      height: 55px;
    }
  }

  ul {
    display: flex;
    li {
      list-style-type: none;
      text-transform: uppercase;
      font-size: 0.8rem;
      font-weight: bold;
      a {
        text-decoration: none;
        color: #000;
        padding: 30px 10px;
        &.active {
          color: $brand-primary;
          border-bottom: 4px solid $brand-primary;
        }
        &:hover {
          color: $brand-primary;
          border-bottom: 4px solid $brand-primary;
        }
      }
    }
  }
</style>