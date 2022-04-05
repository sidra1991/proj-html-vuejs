<template>
  <section>
  <div class="position-testimonial" >
    <div>
      <div class="title-testimonial" >
        <h2>What The Critics Say</h2>
        <h5>TESTIMONIAL FROM AROUND THE WORLD</h5>
      </div>
      <button class="btn-testimonial" >Read All testimonial</button>
    </div>
    <!--card-->
    <div class="testimonial-container" >
      <div class="bg-card " >
        <div class="omb-card" >
          <h2>Best Autor Of His Generation</h2>
          <hr>
          <p>this book will change your perspective on life</p>
          <p>Donec fringilla nunc eu turpis dignissim, at eusmod sapien tincidunt. Maecenas eleifend congue curcus. in vitae enim quis sem pharetra.Curabitur arcu erat, accumasn id imperdiet et, porttitor at sem.</p>
          <p>Donec rutrum congue leo eget malesuada. Vivamus suscipit totor eget felis porttitor volutpat. Nulla quis lorem ut liber. proin eget tortor risus. Praesent sapien massa, convallis a pellentesque nec, egestas non nisi. Donec rutrum congue leo eget malesuada.</p>
          <p>mark justine kilpatrick, <span class="marker-green" > the new york times</span></p>
        </div>
      </div>
      <div>
        <div class="square-container-testimonial" >
          <div class="square-pink" >
            <h3>A True Masterpiece,Bravo!</h3>
            <p>nulla quis lorem ut libero malesuada fegiat. Vivamus magna justo, lacinia eget consectetur sed, convallis at tellus. Vivamus suscipit tortor eget felis porttitor volutpat. Nulla quis lorem ut libero malesuada feug at.</p>
          </div>
          <span class="extra-pink-square" >mark Gerald Hendley, <strong>the Guardian</strong></span>
          <div class="square-pink" >
            <h3>A Unique view ok the world</h3>
            <p>Donec sollicitudin molestie malesuada curabitur arcu erat, accumsan id imperdiet et, porttitor at sem. elementum sed sit amet dui. Nulla quis lorem ut libero malesuada feugiat. vestibulum ac diam sit amet.</p>
          </div>
          <span class="extra-pink-square" >mark Mary Maxey, <strong>the Globe And Mail</strong></span>
        </div>
      </div>
    </div>
  </div>
  </section>
</template>

<script>
export default {
  name: 'testimonialWorld'
}
</script>

<style scoped lang="scss" >

  .position-testimonial{
    width: 60%;
    margin-left: 20%;
    position: relative;
  }

  .title-testimonial{
    display: inline-block;
    margin-top:2rem;
    margin-bottom: 1rem;
    width: 50%;
  }

  .square-container-testimonial{
    margin-left: 2rem;
  }

  h5{
    color:#49a987;
  }

  .testimonial-container{
    display:flex;
    justify-content: space-between;
  }

  .extra-pink-square{
    padding-bottom:2rem;
    display: inline-block;
  }

  .omb-card{
    height: 100%;
    width: 100%;
    padding: 4rem;
    border-radius: 0 0 100px 0;
    background-color: rgba($color: black, $alpha: 0.6);
  }

  .marker-green {
    color: var(--keppel);
  }

  p{
    margin-top: 1rem;
  }

  h2{
    margin-bottom:1rem;
  }

  .square-pink{
    background-color:#fef7e9;
    width: 300px;
    text-align: center;
    padding: 1.5rem;
  }

  .bg-card{
    background-image: url(../assets/author/images/testimonial2-2x.jpg);
    height: 500px;
    width: 560px;
    background-size: cover;
    color: white;
    border-radius: 0 0 100px 0;
  }
</style>
