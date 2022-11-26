<script>
export default {
  name: "AppShop",
  data() {
    return {
      shoplinks: [
        {
          image: "buy-comics-digital-comics.png",
          title: "DIGITAL COMICS",
        },
        {
          image: "buy-comics-merchandise.png",
          title: "DC MERCHANDISE",
        },
        {
          image: "buy-comics-digital-comics.png",
          title: "SUBSCRITION",
        },
        {
          image: "buy-comics-subscriptions.png",
          title: "COMICS SHOP",
        },
        {
          image: "buy-dc-power-visa.svg",
          title: "DC POWER VISA",
        },
      ],
    };
  },
};
</script>

<template>
  <section class="section-shop">
    <nav class="container">
      <!-- <div v-for="(link, index) in shoplinks" class="card">
                <img :src="`../assets/${link.image}`" alt="Image-Shopping">
                <span>{{ link.title }}</span>
            </div> -->
      <div class="card">
        <img
          src="../assets/buy-comics-digital-comics.png"
          alt="Image-Shopping"
        />
        <span>DIGITAL COMICS</span>
      </div>
      <div class="card">
        <img src="../assets/buy-comics-merchandise.png" alt="Image-Shopping" />
        <span>DC MERCHANDISE</span>
      </div>
      <div class="card">
        <img src="../assets/buy-comics-shop-locator.png" alt="Image-Shopping" />
        <span>SUBSCRITION</span>
      </div>
      <div class="card">
        <img
          src="../assets/buy-comics-subscriptions.png"
          alt="Image-Shopping"
        />
        <span>COMICS SHOP</span>
      </div>
      <div class="card">
        <img src="../assets/buy-dc-power-visa.svg" alt="Image-Shopping" />
        <span>DC POWER VISA</span>
      </div>
    </nav>
  </section>
</template>

<style lang="scss" scoped>
.section-shop {
  background-color: var(--third-color);
  padding: 3.125rem;
}

.container {
  display: flex;
  justify-content: space-around;

  .card {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 10rem;
    cursor: pointer;

    img {
      max-width: 2.5rem;
      max-height: 2.5rem;
    }

    span {
      color: var(--first-color);
      padding-left: 0.625rem;
      font-size: 0.75rem;
    }
  }
}
</style>
