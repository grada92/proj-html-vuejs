<template>
  <div class="trainers py-5">
    <div class="container-md text-center">

      <div class="text-white"> <!--Title-Area-->
        <h2>MEET OUR TRAINERS</h2>
        <img src="@/assets/images/divider-xx-red.png" alt="">
        
      </div>

      <div class="row d-flex pt-5">
        <!---Card 1-->
        <div class="col-4">
          <div class="card">

            <img src="@/assets/images/trainer1.jpg" alt="">

            <div class="text-area text-start"> <!--Text-Area--->

              <h5>Ann Baker</h5>
              <h6>Personal Trainer</h6>

              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Eum eligendi facere consequatur!</p>


            </div>
          </div>

        </div>
        <!---Card 2-->
        <div class="col-4">
          <div class="card ">

            <img src="@/assets/images/trainer1.jpg" alt="">

            <div class="text-area text-start"> <!--Text-Area--->

              <h5>Ann Baker</h5>
              <h6>Personal Trainer</h6>

              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Eum eligendi facere consequatur!</p>


            </div>
          </div>

        </div>
        <!---Card 3-->
        <div class="col-4">
          <div class="card">

            <img src="@/assets/images/trainer1.jpg" alt="">

            <div class="text-area text-start"> <!--Text-Area--->

              <h5>Ann Baker</h5>
              <h6>Personal Trainer</h6>

              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Eum eligendi facere consequatur!</p>

              <div class="social-icon d-flex gap-4 px-5 py-3"> <!---Social Icon-->
                <div class="fb text-white">
                  <i class="fa-brands fa-facebook-f"></i>
                </div>

                <div class="tw text-white">
                  <i class="fa-brands fa-twitter"></i>
                </div>

                <div class="ig text-white">
                  <i class="fa-brands fa-instagram"></i>
                </div>


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
name: 'TrainersComponent'
}
</script>

<style lang="scss" scoped>
.trainers {
  background-color:#212425;
}

.card {
  margin: 40px;
  background-color: hsla(210, 6%, 13%, 1); 
  h5 {
    color: white;
    padding: 50px 0px 0px 40px ;
  }
  h6 {
    color: white;
    padding: 0px 40px;
  }
  p {
    color: #aeafae;
    padding: 30px 40px;
  }
}

.fb {
  background-color:  #212425;
  padding: 5px 12px;
}
</style>