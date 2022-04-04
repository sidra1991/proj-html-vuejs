<template>
  <div>
      <div v-for="(el, index) in 3 " :key="index">
          <img src="https://picsum.photos/200/300" alt="">
          <h3>titolo</h3>
          <hr>
          <p>paragrafo</p>

      </div>
  </div>
</template>

<script>
export default {
  name: 'cardEventComponent'

}
</script>

<style>

</style>
