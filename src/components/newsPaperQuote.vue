<template>
<div>
    <div class="news-text" >
        <h3 class="gold-text" >{{papersNews[idShow].title}}</h3>
        <p style="color:white;" >{{papersNews[idShow].content}}</p>
        <h4 class="sub-from" >{{papersNews[idShow].from}}</h4>
    </div>
    <div class="button-news" >
        <button class="undo-next-style" @click="undo ()" ><strong>done</strong> </button>
        <button class="undo-next-style" @click="next ()" ><strong>next</strong></button>
    </div>
</div>
</template>

<script>
export default {
  name: 'newsPaperQuote',
  data () {
    return {
      idShow: '0',
      papersNews: [
        {
          title: 'Damon vaughn',
          content: 'Best-selling author and the most influential public intellectual in the western world right now.',
          from: '-The New York Times'
        },
        {
          title: 'bla bla',
          content: 'lorem ipsum pupo muco nuco',
          from: '-booo'
        },
        {
          title: 'damon vaughn',
          content: 'senza testo',
          from: '-The New York Times'
        }
      ]
    }
  },
  methods: {
    next () {
      if (this.idShow < this.papersNews.length - 1) {
        this.idShow = parseInt(this.idShow) + 1
        console.log(this.idShow)
      } else {
        this.idShow = 0
      }
    },
    undo () {
      if (this.idShow > 0) {
        this.idShow = parseInt(this.idShow) - 1
        console.log(this.idShow)
      } else {
        this.idShow = this.papersNews.length - 1
      }
    }
  }
}
</script>

<style lang="scss" scoped>

  .button-news{
    display: flex;
    justify-content: start;
    margin-bottom: 3rem;
    padding-left: 20%;
  }

  .undo-next-style{
    background-color: var(--black);
    padding: 0.5rem;
    color: white;
    border: transparent;
    margin: 1px
  }

  .news-text{
    font-size: 3em;
    width: 100%;
    line-height: 1.5em;
    padding-left:20%;
    margin-top: 4rem;
    height: 350px;
  }

  .sub-from {
    color: #a3a3a3;
    font-size: 0.5em;
  }

</style>
