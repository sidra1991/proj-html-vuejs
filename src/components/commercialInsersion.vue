<template>
  <div class="container-commercial" >
    <img class="commercial-img"  src="../assets/author/images/book-widget.png" alt="">
    <div class="content-commercial">
      <h3>Latest Book Release</h3>
      <h4>D.VAUGHN AUTOBIOGRAPHY</h4>
      <p>Vestibulum tristique turpis in ipsum egestas lobotis. Duis maximus bibendum volutpat. lorem ipsum dolor sit amet.</p>
    </div>
      <a class="com-btn btn-border-right" >a Buy On Amazon</a>
      <a class="com-btn btn-border-left" >a Buy On AppStore</a>
  </div>
</template>

<script>
export default {
  name: 'commercialIsersion'
}
</script>

<style>
  .container-commercial{
    background-color: white;
    display: flex;
    flex-wrap: wrap;
    padding: 2rem;
  }

  .content-commercial{
    width: 50%;
  }

  .commercial-img{
    width: 50%;
  }

  .com-btn{
    width: 50%;
    border: 1px solid var(--keppel);
    background-color:#f5fcfa ;
    text-decoration: none;
    color: black;
    text-align: center;
    padding: 10px ;
  }

  .btn-border-right{
    border-radius: 10px 0 0 10px;
  }

  .btn-border-left{
    border-radius: 0 10px 10px 0;
  }

</style>
