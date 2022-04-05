<template>
  <section>
    <h2>Dig A Little Deeper Into Damon Vaughn</h2>
    <h4>FIND OUT MORE ABOUT THE AUTHOR HIMSELF</h4>
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
  padding: 2rem;
  text-align: center;
  line-height: 2em;
}

h4{
  color: #49a987;
}
</style>
