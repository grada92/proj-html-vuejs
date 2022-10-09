<template>
<div>
  <div class="box2 pt-3">

    <div class="text-center fitness py-5">
      <h2 class="py-3" >WORLD CLASS Fitness</h2>
        <img src="@/assets/images/divider-xx-red.png" alt="img">
        <div class="text-center col-12">
            <p class="mx-5 py-4 second-text">At Avada Gym, everything we do from top to bottom is of the highest quality to ensure we're equipped to hel you reach your goals of a healthy and fit lifestyles</p>

        </div>

        
     
    </div>
    
    <div class="box-form pb-5">
        <div class="container-fluid text-center pb-5">
          
          <div class="row pb-5 text-center">
            <div class="col-12">
              <img class="triangle" src="@/assets/images/img-triangle.png" alt="triangle">
            </div>
            <div class="col-6 text-end pb-5">
              
              <img class="img-form pb-5" src="@/assets/images/home_img-compressor-400x222.jpg" alt="">

            </div>

            <div class="col-6 text-start pb-5">

              <h5 class="pb- fs-4">Sign Up For a Free Training Session!</h5>
              <p>Name:</p>
              <input class="mb-3" type="text" placeholder="name">
              <p>Email:</p>
              <input type="text" placeholder="Email">
              <div class="py-4 pt-5">
                <button class="btn-start">START NOW</button>
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
name: 'FormComponent'
}
</script>

<style lang="scss" scoped>
.box2 {
  margin-top: 150px;
  color: white;
  padding-top: 10px;
}
.triangle {
  fill: #2e2c2c;
  margin: -55px -20px 0px 0px;
}
.fitness {
  background-color: #25292b;
  height: 370px;
  padding: 0px 540px;
}

.box-form {
  background-color: #232627;
}

input {
  background-color: #2e2c2c;
  width: 430px;
}

.img-form {
  width:500px
}
.btn-start {
  padding: 10px;
  width: 430px;
  background-color: #d5625f;
  color:white;
}
.second-text {
  color: #6b6b6b;
}
</style>