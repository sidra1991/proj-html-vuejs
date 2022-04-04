<template>
  <div>
    <header-main />
    <First-Section class="center" />
    <available-book class="center" />
    <testimonial-world class="center" />
    <cards-events class="center" />
    <subscribe-newsletter class="center" />
    <cards-oter class="center" />
    <recent-articles class="center" />
    <footer-main class="center" />
  </div>
</template>

<script >
import headerMain from './components/headerMain.vue'
import FirstSection from './components/FirstSection'
import AvailableBook from './components/availableBook.vue'
import TestimonialWorld from './components/testimonialWorld.vue'
import CardsEvents from './components/cardsEvents.vue'
import SubscribeNewsletter from './components/subscribeNewsletter.vue'
import CardsOter from './components/cardsOter.vue'
import RecentArticles from './components/recentArticles.vue'
import FooterMain from './components/footerMain.vue'

export default {
  components: {
    headerMain,
    FirstSection,
    AvailableBook,
    TestimonialWorld,
    CardsEvents,
    SubscribeNewsletter,
    CardsOter,
    RecentArticles,
    FooterMain
  }
}
</script>

<style lang="scss">
  :root {
    //color cube
    --white:#ffffff;
    --black: #030303;
    --tundora: #434343;
    --suva_gray: #868586;
    --safron: #f3b329;
    --pumice:#bec6be;
    --blue_lagoon: #027986;
    --corn_harvest:#936c0f;
    --fontain_blue:#51bfc7;
    --alizarin_crimson:#d61a2a;
    //media cut
    --draw_pink:#f3ece3;
    --cod_gray:#1d1c1a;
    --pewter:#96a4a3;
    --sand_dune:#7c6e69;
    --olso_gray:#86888e;
    //material design
    --anzac: #e1aa40;
    --corpion:#5b5b5b;
    --keppel:#3da698;
    --merlin:#453e39;
    --tan:#d5ad91;
  }

  .standard-btn{
    background-color:#49a987 ;
    border: 1px solid transparent;
    padding:0.5rem;
    color: white;
  }

  *{
    margin: 0;
    box-sizing: border-box;
  }

  .gold-text{
    color: var(--safron);
  }

  .center{
    padding-left: 5%;
    padding-right: 5%;
  }
</style>
