<template>
  <div class="box-news pb-5">
    
    <div class="container-md pb-5 card-area text-center">
      <div class="text-center text-white pb-5">
        <img class="triangle" src="@/assets/images/img-content2.png" alt="">
          <h2>PERFORMANCE NEWS</h2> <!--Title--->
          <img src="@/assets/images/divider-xx-red.png" class="pt-3 pb-4" alt="xx-red">
        <div class="row py-5 pt-5">
          <!---Card 1-->
          <div class="col-4">
            <div class="card news-1">

              <img src="@/assets/images/blog1.jpg" alt="blog1">
                <div class="icon-hover d-flex justify-content-center gap-4">
                  <i class="fs-4 text-white fa-solid fa-link"></i>
                  <i class="fs-4 fa-solid fa-magnifying-glass"></i>
                </div>
              <div class="text-area text-start"> <!--Text-Area--->

                <h4>Train with free weights or your body weight?</h4>
              
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste nulla nobis dolorum asperiores commodi placeat sequi aliquam. Eos illo dolore rem sapiente ab. [...]</p>
              
              </div>

            
            </div>

          </div>
          <!---Card 2-->
          <div class="col-4">
            <div class="card news-2">

              <img src="@/assets/images/blog6.jpg" alt="blog6">
                <div class="icon-hover2 d-flex justify-content-center gap-4">
                    <i class="fs-4 text-white fa-solid fa-link"></i>
                    <i class="fs-4 fa-solid fa-magnifying-glass"></i>
                  </div>

              <div class="text-area text-start"> <!--Text-Area--->

                <h4>Nutrional advice that will keep you training</h4>
                
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste nulla nobis dolorum asperiores commodi placeat sequi aliquam. Eos illo dolore rem sapiente ab. [...]</p>
              
              </div>
            </div>
          </div>
          <!---Card 3-->
          <div class="col-4">
            <div class="card ">

              <img src="@/assets/images/trainer4.jpg" alt="trainer4">
              <div class="icon-hover3 d-flex justify-content-center gap-4">
                  <i class="fs-4 text-white fa-solid fa-link"></i>
                  <i class="fs-4 fa-solid fa-magnifying-glass"></i>
                </div>

              <div class="text-area text-start"> <!--Text-Area--->

                <h4>Simple principles for you next workout</h4>
                

                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste nulla nobis dolorum asperiores commodi placeat sequi aliquam. Eos illo dolore rem sapiente ab. [...]</p>

            
              </div>
            </div>

    
          </div>

        </div>

        <div class="row py-5">
          <!---Card 4---->
          <div class="col-4">
            <div class="card news-4">

              <img src="@/assets/images/blog4.jpg" alt="blog4">
              <div class="icon-hover3 d-flex justify-content-center gap-4">
                  <i class="fs-4 text-white fa-solid fa-link"></i>
                  <i class="fs-4 fa-solid fa-magnifying-glass"></i>
                </div>
            
              <div class="text-area text-start"> <!--Text-Area--->

                <h4>To be number one , train like you're number two</h4>
              
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste nulla nobis dolorum asperiores commodi placeat sequi aliquam. Eos illo dolore rem sapiente ab. [...]</p>
               
              </div>

            
            </div>

          </div>
          <!---Card 5----->
          <div class="col-4">
            <div class="card news-5">

              <img src="@/assets/images/trainer3.jpg" alt="trainer3">
              <div class="icon-hover3 d-flex justify-content-center gap-4">
                  <i class="fs-4 text-white fa-solid fa-link"></i>
                  <i class="fs-4 fa-solid fa-magnifying-glass"></i>
                </div>

              <div class="text-area text-start"> <!--Text-Area--->

                <h4>Top 5 mistakes every gym member makes</h4>
                

                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste nulla nobis dolorum asperiores commodi placeat sequi aliquam. Eos illo dolore rem sapiente ab. [...]</p>
              

              

              </div>
            </div>

                

          </div>
          <!---Card 6---->
          <div class="col-4">
            <div class="card news-6">

              <img src="@/assets/images/trainer1.jpg" alt="trainer1">
              <div class="icon-hover3 d-flex justify-content-center gap-4">
                  <i class="fs-4 text-white fa-solid fa-link"></i>
                  <i class="fs-4 fa-solid fa-magnifying-glass"></i>
                </div>

              <div class="text-area text-start"> <!--Text-Area--->

                <h4>The myths of shedding body fat explored</h4>
                

                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste nulla nobis dolorum asperiores commodi placeat sequi aliquam. Eos illo dolore rem sapiente ab. [...]</p>

              

              </div>
            </div>
          </div>

          
        </div>
        <!---BUTTON ARTICLES-->
          <div class="col-12 py-5 pt-5">
            <button class="btn rounded-0 my-5" >READ ALL ARTICLES</button>
          </div>
      </div>

    </div>
  </div>
  
</template>

<script>
export default {
name : 'NewsComponent'
}
</script>

<style lang="scss" scoped>
.box-news {
  background-color: #252a2d;
}

.card {
  background-color: #212425;
  margin: 20px;
  position: relative;

}
h4 {
    color: white;
    padding: 20px 50px 0px 45px ;
  }
h6 {
    color: white;
    padding: 0px 45px;
}
p {
    color: #aeafae;
    padding: 13px 45px;
    line-height: 30px;
 }

.news-1 {
  height: 450px;
}

.news-4 {
  margin: -280px 20px;
}

.news-5 {
  margin: -70px 20px;
}

.news-6 {
  margin: -170px 20px;
}

.btn{
  color: white;
  border: 1px solid white;
}

.triangle {
  margin: -110px 35px 0px 0px;
}

.icon-hover {
  position: absolute;
  z-index: 2;
  top:100px;
  left: 150px;
  opacity: 0;
}

.icon-hover2 {
  position: absolute;
  z-index: 2;
  top:170px;
  left: 150px;
  opacity: 0;
}

.icon-hover3 {
  position: absolute;
  z-index: 2;
  top:130px;
  left: 150px;
  opacity: 0;
}

.card:hover {
  cursor: pointer;
  .icon-hover,.icon-hover2, .icon-hover3{
    opacity: 0.9;
  }
  img {
    opacity: 0.1;
    background: red;
  }
}
</style>