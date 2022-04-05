<template>
  <div>
      <div class="card-event"  v-for="(el, index) in cards " :key="index">
          <img :src="el.imgEvent" :alt="el.imgEvent">
          <h3>{{el.title}}</h3>
          <hr>
          <p>{{el.content}}</p>

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
          imgEvent: '../assets/author/images/event-05.jpg',
          title: 'About Me',
          content: 'Vestibulum ante ipsum'
        },
        {
          imgEvent: '../assets/author/images/event-04.jpg',
          title: 'My Latest Book',
          content: 'Vestibulum ante ipsum'
        },
        {
          imgEvent: '../assets/author/images/event-07.jpg',
          title: 'book Signing',
          content: 'Vestibulum ante ipsum'
        }
      ]
    }
  }
}
</script>

<style>

</style>
