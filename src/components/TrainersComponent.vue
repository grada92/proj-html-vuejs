<template>
  <div class="trainers py-5">
    <div class="container-md text-center">
      
      <div class="text-white"> <!--Title-Area-->
        <h2>MEET OUR TRAINERS</h2>
        <img src="@/assets/images/divider-xx-red.png" alt="">
        
      </div>

      <div class="row d-flex pt-5 pb-5">
        <!---Card 1-->
        <div class="col-4">
          <div class="card">

            <img src="@/assets/images/trainer1.jpg" alt="">

            <div class="text-area text-start"> <!--Text-Area--->

              <h5>Ann Baker</h5>
              <h6>Personal Trainer</h6>

              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Eum eligendi facere consequatur!</p>

              <div class="social-icon d-flex gap-2 px-5 py-3"> <!---Social Icon-->
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
        <!---Card 2-->
        <div class="col-4">
          <div class="card ">

            <img src="@/assets/images/trainer3.jpg" alt="">

            <div class="text-area text-start"> <!--Text-Area--->

              <h5>Anne Warren</h5>
              <h6>Personal Trainer</h6>

              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Eum eligendi facere consequatur!</p>

              <div class="social-icon d-flex gap-2 px-5 py-3"> <!---Social Icon-->
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
        <!---Card 3-->
        <div class="col-4">
          <div class="card">

            <img src="@/assets/images/trainer4.jpg" alt="">

            <div class="text-area text-start"> <!--Text-Area--->

              <h5>Peter Rice</h5>
              <h6>Personal Trainer</h6>

              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Eum eligendi facere consequatur!</p>

              <div class="social-icon d-flex gap-2 px-5 py-3"> <!---Social Icon-->
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
        
        <div class="col-12 py-5"> <!--BUTTON ALL TRAINERS-->
          <button class="btn rounded-0" >VIEW ALL TRAINERS</button>
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
  background-color:#292a2d; 
  h5 {
    color: white;
    padding: 50px 0px 0px 45px ;
  }
  h6 {
    color: white;
    padding: 0px 45px;
  }
  p {
    color: #aeafae;
    padding: 30px 45px;
  }
}
// Social Icon
.fb {
  background-color:  #212425;
  padding: 5px 12px;
  &:hover {
    cursor: pointer;
  }
}

.tw {
  background-color:  #212425;
  padding: 5px 9px;
  &:hover {
    cursor: pointer;
  }
}

.ig {
  background-color:  #212425;
  padding: 5px 11px;
  &:hover {
    cursor: pointer;
  }
}

.btn{
  color: white;
  border: 1px solid white;
}
// HOVER EFFECTS
.card:hover { 
  cursor: pointer;
  img {
  border-bottom: 20px solid #313334;;
  margin-bottom: -20px;
}
}

</style>