<template>
  <div>
      
      <!-- Section for the nav on the top of the main -->
      <section class="top-nav">
        <nav class="container">
          <ul class="row justify-content-center py-3">
            <li class="col-auto">Business</li>
            <li class="col-auto">Design</li>
            <li class="col-auto">Development</li>
            <li class="col-auto">Lifestyle</li>
            <li class="col-auto">Office Productivity</li>
          </ul>
        </nav>
      </section>

      <!-- Jumbtron with the red left side and the img on the right -->
      <section class="jumbotron-affiliate">
        <div class="container">
          <div class="row">
            <div class="offset-1 col-4">
              <h2>Udemy Affiliate Sales</h2>
              <p>Monetize your audience and attract new customers with Udemy!</p>
            </div>
          </div>
        </div>
      </section>

      <!-- Thumbnails Popular Development -->
      <section class="thumbnails">
        <div class="container">
          <div class="row">
            <h2 class="col-12">Popular Development Courses</h2>
            <div class="col-2 thumb">
              <div class="thumb_img">
                <img src="" alt="">
              </div>
              <div class="thumb_text">
                <div class="thumb_text_top">
                  <h6>Development ></h6>
                  <p>random text for now</p>
                </div>
                
                <hr>

                <div class="thumb_text_bot">
                  <img src="" alt="*">
                  <div>
                    <p class="thumb_text_bot-price">$199.99</p>
                    <p class="thumb_text_bot-discount">$100</p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        
        
      </section>

      <!-- Jumbotron for limitless learning -->
      <section class="jumbotron-learning">
        <div class="container">
          <div class="row">
            <div class="offset-2 col-4">
              <h2>Limitless learning, more possibilities</h2>
              <p>Online courses open the opportunity for learning to almost anyone, regardless of their scheduling commitments</p>
              <button>read more</button>
            </div>
          </div>
        </div>
      </section>
      
      <!-- Thumbnails Recent Courses with nav -->
      <section class="thumbnails">
        <div class="container">

          <div class="row text-center">
            <div class="col-12">
              <h2>Recent Courses</h2>
            </div>
          </div>

          <nav class="row justify-content-center">
            <div class="col-auto">
                <a href="">All Categories</a>
            </div>
            <div class="col-auto">
              <a href="">Business</a>
            </div>
            <div class="col-auto">
              <a href="">Design</a>
            </div>
            <div class="col-auto">
              <a href="">Development</a>
            </div>
            <div class="col-auto">
                <a href="">All Categories</a>
            </div>
            <div class="col-auto">
              <a href="">Business</a>
            </div>
            <div class="col-auto">
              <a href="">Design</a>
            </div>
            <div class="col-auto">
              <a href="">Development</a>
            </div>
          </nav>

          <div class="row">
            <div class="col-2 thumb">
              <!--  -->
            </div>
          </div>


          <div class="row text-center">
            <div class="col-12">
              <button>show all</button>
            </div>
          </div>
        
        </div>
      </section>

      <!-- Section for the subscriber -->
      <section class="subscribe">
        <div class="container">
          <div class="row justify-content-center">
            <div class="col-5">
              <h4>subscribe our newsletter</h4>
              <p>There are many variations of passages of Lore Ipsum available, but the majority have suffered alteration in some form, by injected humour, or randomised words</p>
            </div>
            <div class="col-3">
              <h4>your e-mail address</h4>
              <input type="text" placeholder="Enter your E-mail">
              <button>subscribe</button>
            </div>
          </div>
        </div>
      </section>

      <!-- <section class="thumbnails">
        <h2></h2>
        <p></p>
        <div class="thumb">

        </div>
        <button></button>

      </section> -->

      <!-- Section for the two Plan offerts -->
      <section class="plans">
        <div class="container">
          <div class="row">
            <div class="col-6">
              <img src="" alt="">
              <h3>Become an Instructor</h3>
              <p>Teach what you love. Masterstudy gives you the tools to create a course.</p>
              <button>start teaching</button>
            </div>
            <div class="col-6">          
              <img src="" alt="">
              <h3>Access For Business</h3>
              <p>Get unlimited access to 2,500 of top courses for your team.</p>
              <button>doing business</button>
            </div>
          </div>
        </div>
        
      </section>

      <!-- Section of the Jumbotron Investing for your Future -->
      <section class="jumbotron-future">
        <div class="container">
          <div class="row">
            <div class="offset-2 col-5">
              <h3>Investing for your Future</h3>
              <p>It is no exaggeration to say this MasterStudy experience was transformative-both professionally and personally. This workshop will long remain a high point of my life. Thanks again... I am feeling energized and eager to start teaching my class next week. I can't wait to use all of my new teaching tools. I will absolutely recommend this workshop to other educators!</p>
              <h4>Linda Green</h4>
              <p>Product Manager, Apple Inc</p>
            </div>
          </div>
        </div>
      </section>

  </div>
</template>

<script>
export default {

}
</script>

<style scoped lang="scss">
@import '../style/variables.scss';

ul {
  list-style: none;
}
.top-nav {
  background-color: $ebony-clay;
  color: $white;
}


</style>