<template>
  <header class="container">
    <figure>
      <img src="@/assets/img/dc-logo.png" alt="dc-logo">
    </figure>
    <nav>
      <ul>
        <li><a href="#">Characters</a></li>
        <li><a href="#">Comics</a></li>
        <li><a href="#">Movies</a></li>
        <li><a href="#">Tv</a></li>
        <li><a href="#">Games</a></li>
        <li><a href="#">Collectibles</a></li>
        <li><a href="#">Videos</a></li>
        <li><a href="#">Fans</a></li>
        <li><a href="#">News</a></li>
        <li><a href="#">Shop</a></li>
      </ul>
    </nav>
  </header>

  
</template>

<script>
export default {
  name: 'Header',
}
</script>

<style scoped lang="scss">
  header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    height: 100px;
  }

  figure {
    height: 80px;
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
        padding: 40px 10px;
        &:active {
          color: #0282f9;
          border-bottom: 4px solid #0282f9;
        }
        &:hover {
          color: #0282f9;
          border-bottom: 4px solid #0282f9;
        }
      }
    }
  }

</style>