<template>
  <section>
  <div>
    <h2>titolo</h2>
    <h4>sotto titolo</h4>
    <button></button>
  </div>
  <div>
    <!--card-->
    <div class="bg-card" >

    </div>
    <div>
      <div class="square-pink" > <h3>titolo</h3> <p>paragrafop</p> </div>
      <span>testo con piccolo logo</span>
      <div class="square-pink" > <h3>titolo</h3> <p>paragrafop</p> </div>
      <span>testo con piccolo logo</span>
    </div>
  </div>
  </section>
</template>

<script>
export default {
  name: 'testimonialWorld'
}
</script>

<style scoped lang="scss" >
  section{
    background-color: blue;
  }

  .bg-card{
    background-image: url(../assets/author/images/testimonial2-2x.jpg);
    height: 100px;
    width: 100px;
    background-size: cover;
  }
</style>
