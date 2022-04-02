<template>
  <div>
    <header-main class="center" />
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
  *{
    margin: 0;
    box-sizing: border-box;
  }

  .center{
    padding-left: 5%;
    padding-right: 5%;
  }
</style>
