<template>
 <div class="container-fluid">
    <div class="row">

    <div class="box-reviews text-center py-5">
      <div class="box-text py-5">

        <h2>REAL WORLD RESULTS</h2>
        <img src="@/assets/images/divider-xx-red.png" alt="">


      </div>

      <div class="box-user mx-5 pb-5">
        <div class="d-flex reviews justify-content-center pt-5">
                      <!--CARD 1-->
          <div class="card col-6 text-start">
            <div>
              <img src="@/assets/images/review_1-compressor.jpg" alt="img1">
            </div>

              <div>
                  <p>"The trainers at Avada Gym have helped me reach my fitness goals beyond anything i could of hoped for, I love it"</p>
                  <h6>- Tara Smith</h6>
                </div>
                    
          </div>
                      <!--CARD 2-->
          <div class="card col-6 text-start">
            <div>
                <img src="@/assets/images/review_3-compressor-2.jpg" alt="img2">
            </div>

              <div>
                <p>"The atmosphere at Avada Gym is amazing, the people are even better. All in all , it is a great place to work out"</p>
                <h6>- Simon Chel</h6>
              </div>
          </div>


                
                
        </div>

        <div class="d-flex reviews justify-content-center pb-5">
                      <!--CARD 3-->
          <div class="card col-6 text-start">
            <div>
              <img src="@/assets/images/review_2-compressor.jpg" alt="img3">
            </div>

              <div>
                  <p>"The facilities at Avada Gym stood out to me the most. They are well maintained and have high quality equipment"</p>
                  <h6>- Jen Wirth</h6>
                </div>
                    
          </div>
                      <!--CARD 4-->
          <div class="card col-6 text-start">
            <div>
                <img src="@/assets/images/review_4-compressor-2.jpg" alt="img4">
            </div>

              <div>
                <p>"No bad things to say about Avada Gym , they are top notch at every corner and truly take care of their customers"</p>
                <h6>- Jeff Glum</h6>
              </div>
          </div>


                
                
        </div>

      
      </div>

    

      
    



    </div>
  </div>
</div>
  
</template>

<script>
export default {
name : 'ReviewsComponent'
}
</script>

<style lang="scss" scoped>
.box-reviews {
  background-color: #212425;
  padding: 0px 100px;
}

h2 {
  color: white;
}

.card {
  padding: 15px ;
  background-color: rgb(25, 26, 28);
  color: #aeafae;
  font-size: 11px;
  display: flex;
  flex-direction: row;
  margin: 10px;
  width: 550px;
  p {
    margin: 10px;
    line-height: 20px;
    font-style: oblique;
  }
  h6 {
    margin: 10px;
  }
}

</style>
