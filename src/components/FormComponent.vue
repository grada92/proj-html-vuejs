<template>
<div>
  <div class="box2">

    <div class="text-center fitness py-5">
      <h2>WORLD CLASS Fitness</h2>
        <img src="@/assets/images/divider-xx-red.png" alt="img">
        <div class="text-center col-12">
            <p class="mx-5">At Avada Gym, everything we do from top to bottom is of the highest quality to ensure we're equipped to hel you reach your goals of a healthy and fit lifestyles</p>

        </div>

          
     
    </div>

    <div class="box-form py-5">
        <div class="container-fluid text-center py-5">

          <div class="row py-5">

            <div class="col-6 text-end">
              <img src="@/assets/images/home_img-compressor-400x222.jpg" alt="">

            </div>

            <div class="col-6 text-start">

              <h5 class="pb-2">Sign Up For a Free Training Session!</h5>
              <p>Name:</p>
              <input class="mb-3" type="text" placeholder="name">
              <p>Email:</p>
              <input type="text" placeholder="Email">
              <div class="py-4">
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

.fitness {
  background-color: #2e2c2c;
}

.box-form {
  background-color: hsla(0, 0%, 12%, 1);
}

input {
  background-color: #2e2c2c;
  width: 330px;
}

.btn-start {
  width: 330px;
  background-color: #d5625f;
  color:white;
}
</style>