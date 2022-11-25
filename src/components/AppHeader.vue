<script>
import AppHero from './AppHero.vue';
export default {
  name: 'AppHeader',
  components: {
    AppHero,
  },
  data() {
    return{
      links: [
        {
          href: '#',
          label: 'CHARACTERS',
          active: false
        },
        {
          href: '#',
          label: 'COMICS',
          active: true
        },
        {
          href: '#',
          label: 'MOVIES',
          active: false
        },
        {
          href: '#',
          label: 'TV',
          active: false
        },
        {
          href: '#',
          label: 'GAMES',
          active: false
        },
        {
          href: '#',
          label: 'VIDEO',
          active: false
        },
        {
          href: '#',
          label: 'FANS',
          active: false
        },
        {
          href: '#',
          label: 'NEWS',
          active: false
        },
        {
          href: '#',
          label: 'SHOP',
          active: false
        }
      ]
    }
  },
  methods: {
    changeLink(index) {
      this.links.forEach((elm, i) =>{
        if( i === index ) {
          elm.active = true;
        } else {
          elm.active = false;
        }
      });
    }
  }
}

</script>

<template>
  <header>
    <div class="container">
      <img src="../assets/dc-logo.png" alt="Logo">
      <ul>
        <li v-for="(link, index) in links" :class="{active: link.active}" @click.prevent="changeLink(index)"><a :href="link.href"><strong>{{ link.label }}</strong></a></li>
      </ul>
    </div>
  </header>
  <AppHero/>
</template>

<style lang="scss" scoped>

.container {
  display: flex;
  justify-content: space-between;
  align-items: center;

  img{
    max-width: 4.375rem;
  }

  ul {
    display: flex;
    list-style: none;

    li {
      padding: 2.1875rem .625rem 2.1875rem .625rem;
      font-size: .75rem;
      font-style: bold;

      a {
        text-decoration-line: none;
        color: var(--second-color);
      }
      &.active{
        color: var(--third-color);
        border-bottom: .25rem solid var(--third-color);
      }
    }
  }
}

</style>