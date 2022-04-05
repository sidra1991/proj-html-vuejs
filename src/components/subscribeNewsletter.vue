<template>
  <section>
    <div class="obscure">
      <h2>Subscibe to my</h2>
      <h2>newsletter</h2>
      <h4 class="gold-text" >BE NOTIFIED ABOUT BOOK SIGNING TOUR DATE </h4>
      <input class="subscibe-input"  type="email" placeholder="insert your email...*"><a class="standard-btn" >subscribe</a>
      <p class="gary-text" >Donec fringila nuneu turpis dignissim, at eusmod spien tincidunt.</p>
    </div>
  </section>
</template>

<script>
export default {
  name: 'subscibeNewsletter'
}
</script>

<style scoped lang="scss" >
  section{
    background-image: url(../assets/author/images/banner-2.jpg);
    text-align: center;
    color: white;
    height: 300px;
  }

  .gray-text{
    color:#657d8e ;
  }

  .subscibe-input{
    height: 2.8em;
    margin:10px;
  }

  .obscure{
    background-color: rgba($color: black, $alpha: 0.4);
    width: 100%;
    height: 100%;
    padding: 2rem;
  }

</style>
