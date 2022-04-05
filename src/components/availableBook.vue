<template>
  <section>
    <!-- 4 loghi probabilmente cliccabili con sotto un backgraund con immagine alla cui destra cè un titolo-sottotitolo-testo seguito da 3 loghi-->
    <div class="logos" >
      <img src="../assets/author/images/ebay-logotan-2x-200x66.png" alt="">
      <img src="../assets/author/images/audible-logotan-2x-200x66.png" alt="">
      <img src="../assets/author/images/bb-logotan-2x-200x66.png" alt="">
      <img src="../assets/author/images/kindlefire-logotan-2x-200x66.png" alt="">
    </div>
    <div class="bg-imm" >
      <img src="../assets/author/images/audible-app-2x-400x418.png" alt="">
      <div class="available-text" >
        <h2 style="color:white;" >New Audiobook</h2>
        <h5 class="gold-text" >NO TIME TO READ? NO PROBLEM. LISTEN TO IT</h5>
        <p class="paragrap-available">Donec fringilla nunc eu turpis dignissim, at euismod sapien tincidunt. maecenas eleifed congue cursus.</p>
        <img class="logo-bottom" src="../assets/author/images/audible-logo.png" alt="">
        <img class="logo-bottom" src="../assets/author/images/bn-logo-tall.png" alt="">
        <img class="logo-bottom" src="../assets/author/images/kindle-logo-tall.png" alt="">
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'avaibleBook'
}
</script>

<style scoped lang="scss" >
  .logos{
    padding: 1rem;
    text-align: center;
  }

  .logo-bottom{
    margin-top:3rem;
    margin-left: 2rem;
  }

  .available-text{
    text-align: center;
    line-height: 2rem;
    padding-top: 6rem;
  }

  .paragrap-available{
    color:var(--suva_gray);
    line-height: 1rem;
    width: 370px;
    margin-left: 4rem;
  }

  section{
    padding: 0;
    background-color: var(--draw_pink)
  }

  .bg-imm{
    text-align: center;
    padding-top:2rem;
    width: 100%;
    background-image: url(../assets/author/images/banner.jpg);
    display: flex;
    justify-content: center;
  }
</style>
