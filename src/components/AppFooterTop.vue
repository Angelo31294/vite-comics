<script>
export default {
  name: "AppFooterTop",
};
</script>

<template>
  <section class="container footer-top">
    <!---------- Container Left ---------->
    <div class="container-left">
      <ul>
        <li><h4>DC COMICS</h4></li>
        <li>
          <a href=""><small>Characters</small></a>
        </li>
        <li>
          <a href=""><small>Comics</small></a>
        </li>
        <li>
          <a href=""><small>Movies</small></a>
        </li>
        <li>
          <a href=""><small>TV</small></a>
        </li>
        <li>
          <a href=""><small>Games</small></a>
        </li>
        <li>
          <a href=""><small>Videos</small></a>
        </li>
        <li>
          <a href=""><small>News</small></a>
        </li>
      </ul>
      <ul>
        <li><h4>DC</h4></li>
        <li>
          <a href=""><small>Term of Use</small></a>
        </li>
        <li>
          <a href=""><small>Privacy Policy (New)</small></a>
        </li>
        <li>
          <a href=""><small>Ad Choices</small></a>
        </li>
        <li>
          <a href=""><small>Advertising</small></a>
        </li>
        <li>
          <a href=""><small>Job</small></a>
        </li>
        <li>
          <a href=""><small>Subscription</small></a>
        </li>
        <li>
          <a href=""><small>Talent Workshops</small></a>
        </li>
        <li>
          <a href=""><small>CPSC Certificates</small></a>
        </li>
        <li>
          <a href=""><small>Rating</small></a>
        </li>
        <li>
          <a href=""><small>Shop Help</small></a>
        </li>
        <li>
          <a href=""><small>Contact Us</small></a>
        </li>
      </ul>
      <ul>
        <li><h4>SITES</h4></li>
        <li>
          <a href=""><small>DC</small></a>
        </li>
        <li>
          <a href=""><small>MAD Magazine</small></a>
        </li>
        <li>
          <a href=""><small>DC kids</small></a>
        </li>
        <li>
          <a href=""><small>DC Univers</small></a>
        </li>
        <li>
          <a href=""><small>DC Power Visa</small></a>
        </li>
      </ul>
      <ul>
        <li><h4>SHOP</h4></li>
        <li>
          <a href=""><small>Shop DC</small></a>
        </li>
        <li>
          <a href=""><small>Shop DC Collectibles</small></a>
        </li>
      </ul>
    </div>
    <!---------- /Container Left ---------->

    <!---------- Container Right ---------->
    <div class="container-rt"></div>
    <!---------- /Container Right ---------->
  </section>
</template>

<style lang="scss" scoped>
.footer-top {
  max-height: 25rem;
  display: flex;
  justify-content: space-between;

  .container-left {
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
    padding: 1.25rem 0;

    ul {
      list-style: none;
      width: 30%;
      li {
        h4 {
          color: var(--first-color);
        }

        a {
          text-decoration: none;
          color: var(--fourth-color);
          font-size: 0.6875rem;
        }
      }
    }
  }
  .container-rt {
    background-image: url(../assets/dc-logo-bg.png);
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
  }
}
</style>
