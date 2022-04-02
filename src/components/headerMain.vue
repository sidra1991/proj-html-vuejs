<template>
  <header>
    <div class="header-div" >
      <!-- logo a sinistra -->
      <img src="" alt="">
      <!-- nav bar a destra -->
    </div>
    <div class="header-div">
      <nav-bar />
      <!-- 2 pendici ad estrema destra  -->
      <!-- un riqua in grado di cambiare non capisco cosa forse le frasi-->
      <!-- un riquadro in basso a destra contenente un articolo in vendita -->
    </div>
  </header>
</template>

<script>
import navBar from './navBar.vue'
export default {
  components: { navBar },
  name: 'headerMain'
}
</script>

<style scoped lang="scss">
  header{
    background-image: url(../../public/author/images/hero-07-2x.jpg);
    height: 100vh;
    background-size: cover;
  }

  .header-div{
    width: 50%;
    height: 100%;
    display: inline-block;
  }

</style>
