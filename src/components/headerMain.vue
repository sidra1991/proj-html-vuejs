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
      <div class="btn-header-right" >
        <button class="ex-btn" >a1 demos</button>
      </div>
      <div class="btn-header-right" >
        <button class="ex-btn" > <span class="gr-text"> $ <strong>39</strong></span> On Sale  </button>
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
    display: inline-block;
  }

  .ex-btn{
    display: block;
    padding: 1rem;
    width: 100px;
    height: 100px;
  }

  .btn-header-right{
    display: flex;
    justify-content: end;
    flex-wrap: wrap;
    margin: 10px;
  }

  .gr-text{
    color: lightgreen;
    vertical-align: top;
    strong{
      font-size:2rem;
    }
  }

</style>
