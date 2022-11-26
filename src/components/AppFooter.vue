<script>
import AppFooterTop from "./AppFooterTop.vue";
import AppFooterBottom from "./AppFooterBottom.vue";
export default {
  name: "AppFooter",
  components: {
    AppFooterTop,
    AppFooterBottom,
  },
};
</script>

<template>
  <footer>
    <AppFooterTop />
  </footer>
  <AppFooterBottom />
</template>

<style lang="scss" scoped>
footer {
  background-image: url(../assets/footer-bg.jpg);
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
}
</style>
