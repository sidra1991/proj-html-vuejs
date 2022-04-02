<template>
<!-- da sistemare -->
  <nav>
    <ul>
      <li v-for="(link, index) in arrLinks" :key="index" ><a :href="link.link">{{link.name}}</a></li>
    </ul>
  </nav>
</template>

<script>
export default {
  name: 'navBar',
  data () {
    return {
      arrLinks: [
        {
          name: 'Home',
          link: '#'
        },
        {
          name: 'About Me',
          link: '#'
        },
        {
          name: 'Testimonials',
          link: '#'
        },
        {
          name: 'My Blog',
          link: '#'
        },
        {
          name: 'Meetups',
          link: '#'
        },
        {
          name: 'Shop',
          link: '#'
        },
        {
          name: 'Contact Me',
          link: '#'
        },
        {
          name: 'carrello',
          link: '#'
        }
      ]
    }
  }
}
</script>

<style scoped legn="scss">
  ul{
    list-style: none;
    padding: 0;
    display: flex;
    justify-content: space-around;
  }
  a{
    display: inline-block;
    padding-top:1rem;
    text-decoration: none;
    color:white;
    border-top:2px solid transparent;
  }

  a:hover{
    color: var(--anzac);
    border-top:2px solid var(--anzac);
  }

</style>
