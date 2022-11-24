<script>
export default {
  name: 'AppMain'
}
</script>

<template>
  <main class="container">
    <h1>--> Content goes here</h1>
  </main>
  <nav class="container main-nav">
    <div class="card">
      <img src="../assets/buy-comics-digital-comics.png" alt="Image-Shopping">
      <span>DIGITAL COMICS</span>
    </div>
    <div class="card">
      <img src="../assets/buy-comics-merchandise.png" alt="Image-Shopping">
      <span>DC MERCHANDISE</span>
    </div>
    <div class="card">
      <img src="../assets/buy-comics-shop-locator.png" alt="Image-Shopping">
      <span>SUBSCRITION</span>
    </div>
    <div class="card">
      <img src="../assets/buy-comics-subscriptions.png" alt="Image-Shopping">
      <span>COMICS SHOP</span>
    </div>
    <div class="card">
      <img src="../assets/buy-dc-power-visa.svg" alt="Image-Shopping">
      <span>DC POWER VISA</span>
    </div>
  </nav>
</template>

<style lang="scss" scoped>
main{
  background-color: var(--second-color);
  color: var(--first-color);
  padding: 2.5rem;
}

.main-nav{
  display: flex;
  justify-content: space-around;
  background-color: var(--third-color);
  padding: 3.125rem;
  
  .card{
    display: flex;
    justify-content: center;
    align-items: center;
    width: 10rem;

    img{
      max-width: 2.5rem;
      max-height: 2.5rem;
    }

    span{
      color: var(--first-color);
      padding-left: .625rem;
      font-size: .75rem;
    }

  }
}
</style>