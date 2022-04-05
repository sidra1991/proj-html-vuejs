<template>
  <section>
    <h3>Upcoming Events</h3>
    <h4 class="gold-text" >Meet the author in person</h4>
    <card-event-component />
  </section>
</template>

<script>
import cardEventComponent from './cardEventComponent.vue'
export default {
  components: { cardEventComponent },
  name: 'cardsEvent'
}
</script>

<style scoped lang="scss" >
  section{
    text-align: center;
    background-color:#fef7e9 ;
    padding:2rem;
    margin-top: 2rem;
  }
</style>
