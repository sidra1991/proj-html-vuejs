<template>
  <div>
      <div v-for="(el, index) in 3 " :key="index">
          <img src="https://picsum.photos/200/300" alt="">
          <h3>titolo</h3>
          <hr>
          <p>paragrafo</p>

      </div>
  </div>
</template>

<script>
export default {
  name: 'cardEventComponent',
  data (){
    return{
      cards:[
        {
          img:'https://picsum.photos/200/300',
          title:'chicago Book signing',
          content:'mauris blandit aliquet elit, eget tincidunt nibh pulvinar a.Mauris blandit elit, eget tincidunt nibh pulvinar a nulla.'
        },
        {
          img:'https://picsum.photos/200/300',
          title:'Meet & Greet With Amanda',
          content:'Mauris blandit aliquet elit, eget tincidunt nibh pulvinar a.Prasent sapien massa, convallis a pellentesque nec egestas.'
        },
        {
          img:'https://picsum.photos/200/300',
          title:'chicago Book signing',
          content:'mauris blandit aliquet elit, eget tincidunt nibh pulvinar a.Mauris blandit elit, eget tincidunt nibh pulvinar a nulla.'
        }
      ]
    }
  }

}
</script>

<style>

</style>
