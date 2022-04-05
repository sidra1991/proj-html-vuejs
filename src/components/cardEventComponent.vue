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
  name: 'cardEventComponent',
  data () {
    return {
      cards: [
        {
          imgEvent: '../assets/author/images/event-05.jpg',
          title: 'chicago Book signing',
          content: 'mauris blandit aliquet elit, eget tincidunt nibh pulvinar a.Prasent sapien massa, convallis a pellentesque nec, egestas.'
        },
        {
          imgEvent: '../assets/author/images/event-04.jpg',
          title: 'Meet & Greet With Amanda',
          content: 'Mauris blandit aliquet elit, eget tincidunt nibh pulvinar a.Prasent sapien massa, convallis a pellentesque nec egestas.'
        },
        {
          imgEvent: '../assets/author/images/event-07.jpg',
          title: 'Open Book: Dialogue',
          content: 'Mauris blandit aliquet elit, eget tincidunt nibh pulvinar a.Mauris blandit alique elit, eget tincidunt nibh pulvinar a nulla.'
        }
      ]
    }
  }

}
</script>

<style>
  .card-event{
    text-align: center;
    width: 320px;
    height: 600px;
    display:inline-block;
    margin: 1rem;
    line-height: 1.5rem;
  }
</style>
