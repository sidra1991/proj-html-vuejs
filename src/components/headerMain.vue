<template>
  <header>
    <div class="header-div" >
      <!-- logo a sinistra -->
      <img src="../assets/author/images/author-logo-round-small.png" alt="">
      <!-- la citazione di giornale-->
      <news-paper-quote />
    </div>
    <div class="header-div">
      <nav-bar />
      <!-- 2 pendici ad estrema destra  -->
      <div>
        <button>a1</button><button>a2</button>
      </div>
      <!-- un riquadro in basso a destra contenente un articolo in vendita -->
      <commercial-insersion />
    </div>
  </header>
</template>

<script>
import navBar from './navBar.vue'
import NewsPaperQuote from './newsPaperQuote.vue'
import commercialInsersion from './commercialInsersion.vue'
export default {
  components: { navBar, NewsPaperQuote, commercialInsersion },
  name: 'headerMain'
}
</script>

<style scoped lang="scss">
  header{
    background-image: url(../assets/author/images/hero-07-2x.jpg);
    background-size: cover;
    display: flex;
  }

  .header-div{
    width: 50%;
    height: 100%;
    display: inline-block;
  }

</style>
