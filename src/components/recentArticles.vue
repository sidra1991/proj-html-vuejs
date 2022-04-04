<template>
  <section>
    <div> <h2>titolo</h2> <h3>sottotitolo</h3> </div>
    <div> <button></button> </div>

    <div>
      <div class="card-big">
        <img src="https://picsum.photos/400/400" alt="">
        <h3>titolo</h3>
        <p class="dat" > data </p>
        <p>paragrafo</p>
      </div>
      <div>
        <div class="card-small" >
          <img src="https://picsum.photos/200/200" alt="">
          <h3>titolo</h3>
          <p class="dat" > data </p>
        </div>
        <div class="card-small" >
          <img src="https://picsum.photos/200/200" alt="">
          <h3>titolo</h3>
          <p class="dat" > data </p>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'recentArticles'
}
</script>

<style scoped lang="scss" >
  section{
    background-color: blue;
  }
</style>
