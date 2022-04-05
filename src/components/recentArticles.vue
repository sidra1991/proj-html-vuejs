<template>
  <section>
    <div class="intestation" >
      <div>
        <h2>Recent Articles</h2>
        <h3>READ THE LATEST ENTRIES</h3>
      </div>
      <div>
        <button class="btn-testimonial"  >All Articles</button>
      </div>
    </div>
    <div class="flex-box" >
      <div class="small-tumble">
        <img src="../assets/author/images/20-Tips-800x471.jpg" alt="">
        <h3>20 Creativity tips</h3>
        <p class="dat" >By admin | october 24th, 2019 | categories: <strong>Event, tips & Tricks</strong> </p>
        <p class=" text-tumble" >Vestibulum ante ipsum primis in caucibus orci luctus et ultrices posuere cubilia Curae; Donec velit neque, auctor sit amet aliquam vel, ullamcorper sit amet.</p>
      </div>
      <div class="small-tumble" >
        <div class="card-small" >
          <img src="../assets/author/images/thumb-13-2x-320x202.jpg" alt="">
          <h3>What's On your Booklist?</h3>
          <p class="dat" > October 24th, 2019| 0 Comments </p>
        </div>
        <div class="card-small" >
          <img src="../assets/author/images/thumb-08-2x-320x202.jpg" alt="">
          <h3>instabul Travel Guide</h3>
          <p class="dat" > October 24th, 2019 | 0 Comments </p>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'recentArticles'
}
</script>

<style scoped lang="scss" >
  section{
    background-color: #fef7e9;
  }

  .text-tumble{
    width: 560px;
  }

  .flex-box{
    display: flex;
    justify-content: center;
  }

  .intestation {
    margin-left: 15%;
    margin-right: 15%;
    padding-top: 3rem;
    display: flex;
    justify-content: space-between;
  }

  .small-tumble{
    background-color: white;
    margin:1rem;
    line-height: 2em;
    padding: 1rem;
  }
</style>
