<template>
<div>
    <div>
        <h3>{{papersNews[idShow].title}}</h3>
        <p>{{papersNews[idShow].content}}</p>
        <h4>{{papersNews[idShow].from}}</h4>
    </div>
    <div>
        <button @click="undo ()" ><strong>done</strong> </button>
        <button @click="next ()" ><strong>next</strong></button>
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
          title: 'damon vaughn',
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

<style>
</style>
