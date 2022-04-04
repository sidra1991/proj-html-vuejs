<template>
  <section>
    <h2>titolo</h2>
    <h3>sottotitolo</h3>
    <cards-oter-component />
  </section>
</template>

<script>
import cardsOterComponent from './cardsOterComponent.vue'
export default {
  components: { cardsOterComponent },
  name: 'cardsOter'
}
</script>

<style scoped lang="scss" >
  section{
    background-color: red;
  }
</style>
