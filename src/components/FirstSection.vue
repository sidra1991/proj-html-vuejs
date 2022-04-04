<template>
  <section>
    <!-- un testo con titlo e bottone , stile titolo in comune con ttitolo in header -->
    <div class="frist" >
      <h2 class="gold-text" >Home About Damon Vaughn</h2>
      <p>Damon Vaughn is a professor of psichology at the University ok Toronto, a linical psichologist and the author of multi-milion copy bestseller "The story of my life"</p>
      <a class="standard-btn" >Meet The Author</a>
    </div>
  </section>
</template>

<script>
export default {
  name: 'FirstSection'
}
</script>

<style scoped lang="scss" >

  section{
    padding-top: 3rem;
    padding-bottom: 3rem;
    text-align: center;
    display: flex;
    justify-content: center;
  }

  .frist {
    width: 650px;
    h2{
      margin-bottom: 10px;
    }
    p{
      margin-bottom: 1rem;
    }
  }

</style>
