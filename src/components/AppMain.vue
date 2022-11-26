<script>
import AppSeries from "./AppSeries.vue";
import AppShop from "./AppShop.vue";
export default {
  name: "AppMain",
  components: {
    AppSeries,
    AppShop,
  },
};
</script>

<template>
  <main>
    <AppSeries />
    <button type="submit">LOAD MORE</button>
  </main>
  <AppShop />
</template>

<style lang="scss" scoped>
main {
  background-color: var(--second-color);
  color: var(--first-color);
  padding: 2.5rem;
  text-align: center;

  button {
    color: var(--first-color);
    background-color: var(--third-color);
    border: none;
    margin-top: 2.5rem;
    padding: 0.3125rem 0.9375rem;
    text-align: center;
    cursor: pointer;
  }
}
</style>
