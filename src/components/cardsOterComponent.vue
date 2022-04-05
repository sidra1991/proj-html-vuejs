<template>
  <div class="card-oter-container" >
      <div class="card-oter"  v-for="(el, index) in cards " :key="index">
          <img class="back-img" :src="el.im_goter" :alt="el.im_goter">
          <h3>{{el.title}}</h3>
          <hr>
          <p class="gold-text" >{{el.content}}</p>

      </div>
  </div>
</template>

<script>
export default {
  name: 'cardOterComponent',
  data () {
    return {
      cards: [
        {
          im_goter: '../assets/author/images/box-1.jpg',
          title: 'About Me',
          content: 'Vestibulum ante ipsum'
        },
        {
          im_goter: '../assets/author/images/box-4.jpg',
          title: 'My Latest Book',
          content: 'Vestibulum ante ipsum'
        },
        {
          im_goter: '../assets/author/images/box-3.jpg',
          title: 'book Signing',
          content: 'Vestibulum ante ipsum'
        }
      ]
    }
  }
}
</script>

<style scoped>
  .card-oter-container{
    display:flex;
    justify-content: center;
  }

  .card-oter{
    margin: 1rem;
    position: relative;
    text-align: center;
    height: 200px;
    width: 200px;
    color: white;
  }

  .back-img{
    position: absolute;
    height: 100%;
    width: 100%;
    z-index: -1;
  }
</style>
