<template>
  <section>
    <!-- 4 loghi probabilmente cliccabili con sotto un backgraund con immagine alla cui destra cè un titolo-sottotitolo-testo seguito da 3 loghi-->
    <div>
      <img src="../assets/author/images/ebay-logotan-2x.png" alt="">
      <img src="../assets/author/images/audible-logotan-2x.png" alt="">
      <img src="../assets/author/images/bb-logotan-2x.png" alt="">
      <img src="../assets/author/images/kindlefire-logotan-2x.png" alt="">
    </div>
    <div class="bg-imm" >
      <img src="../assets/author/images/audible-app-2x.png" alt="">
      <h2>titolo</h2>
      <h3>sottotitolo</h3>
      <p>paragrafo</p>
      <img src="../assets/author/images/audible-logotan-2x.png" alt="">
      <img src="../assets/author/images/bb-logotan-2x.png" alt="">
      <img src="../assets/author/images/kindlefire-logotan-2x.png" alt="">
    </div>
  </section>
</template>

<script>
export default {
  name: 'avaibleBook'
}
</script>

<style scoped lang="scss" >
  section{
    padding: 0;
    background-color: yellow
  }

  .bg-imm{
    width: 100%;
    background-image: url(../assets/author/images/banner.jpg);
  }
</style>
