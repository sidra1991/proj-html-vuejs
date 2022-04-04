<template>
  <header>
    <div class="shadow">
      <div class="header-div" >
        <!-- logo a sinistra -->
        <img class="logo" src="../assets/author/images/author-logo-round-small.png" alt="">
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
        <commercial-insersion class="window-right-bottom" />
      </div>
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
  }

  .logo{
    margin-left: 15%;
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

  .shadow{
    position: relative;
    height: 100%;
    width: 100%;
    background-color: rgba($color: black, $alpha: 0.6);
    display: flex;
  }

  .window-right-bottom{
    position: absolute;
    right: 0;
    bottom: 0;
    width: 30%;
  }

</style>
