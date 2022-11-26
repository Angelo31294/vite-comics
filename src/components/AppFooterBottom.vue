<script>
export default {
  name: "AppFooterBottom",
};
</script>

<template>
  <section class="footer-bottom">
    <div class="container">
      <div>
        <button type="submit">SIGN-UP NOW</button>
      </div>
      <ul>
        <li>
          <a href="#"><strong>FOLLOW US</strong></a>
        </li>
        <li>
          <a href="#">
            <img src="../assets/footer-facebook.png" alt="Facebook" />
          </a>
        </li>
        <li>
          <a href="#">
            <img src="../assets/footer-periscope.png" alt="Facebook" />
          </a>
        </li>
        <li>
          <a href="#">
            <img src="../assets/footer-twitter.png" alt="Facebook" />
          </a>
        </li>
        <li>
          <a href="#">
            <img src="../assets/footer-pinterest.png" alt="Facebook" />
          </a>
        </li>
        <li>
          <a href="#">
            <img src="../assets/footer-youtube.png" alt="Facebook" />
          </a>
        </li>
      </ul>
    </div>
  </section>
</template>

<style lang="scss" scoped>
.footer-bottom {
  background-color: var(--fifth-color);
  padding: 1.25rem;
}

.container {
  display: flex;
  justify-content: space-between;

  ul {
    list-style: none;
    display: flex;
    justify-content: space-around;
    align-items: center;
    width: 30%;

    a {
      text-decoration: none;
      text-align: center;
      color: var(--third-color);
    }
  }
}

img {
  width: 85%;
}

button {
  background-color: transparent;
  border-color: var(--third-color);
  color: var(--first-color);
  padding: 0.625rem;
  cursor: pointer;
}
</style>
