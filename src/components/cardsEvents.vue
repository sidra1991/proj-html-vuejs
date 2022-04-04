<template>
  <section>
    <h3>titolo</h3>
    <h4>sottotitolo</h4>
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
    background-color: red;
  }
</style>
