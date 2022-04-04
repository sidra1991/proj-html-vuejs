<template>
<div>
    <div>
        <h3>{{papersNews[idShow].title}}</h3>
        <p>{{papersNews[idShow].content}}</p>
        <h4>{{papersNews[idShow].from}}</h4>
    </div>
    <div>
        <button><strong>done</strong> </button>
        <button><strong>next</strong></button>
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
        }
      ]
    }
  }
}
</script>

<style>
</style>
