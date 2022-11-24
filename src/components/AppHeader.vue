<script>
export default {
  name: 'AppHeader'
}
</script>

<template>
  <header class="container">
    <img src="../assets/dc-logo.png" alt="Logo">
    <ul>
      <li><a href="">CHARACTERS</a></li>
      <li><a class="active" href="">COMICS</a></li>
      <li><a href="">MOVIES</a></li>
      <li><a href="">TV</a></li>
      <li><a href="">GAMES</a></li>
      <li><a href="">COLLECTIBLES</a></li>
      <li><a href="">VIDEO</a></li>
      <li><a href="">FANS</a></li>
      <li><a href="">NEWS</a></li>
      <li><a href="">SHOP</a></li>
    </ul>
  </header>
</template>

<style lang="scss" scoped>
header{
  display: flex;
  justify-content: space-between;
  padding: .625rem .3125rem;

  img{
    width: 5rem;
    height: 5rem;
  }

  ul{
    display: flex;
    list-style: none;
    align-items: center;

    a{
      display: inline-block;
      padding: .625rem;
      text-decoration: none;
      color: var(--second-color);
      font-size: .75rem;

      &.active{
        color: var(--third-color);
        border-bottom: 3px solid var(--third-color);
      }
    }
  }
}


</style>