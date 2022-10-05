<template>
 <div class="container-fluid">
  <div class="row">

    <div class="box-reviews text-center py-5">
    <div class="box-text py-5">

      <h2>REAL WORLD RESULTS</h2>
    <img src="@/assets/images/divider-xx-red.png" alt="">


    </div>

    <div class="box-user mx-5" >
      <div class="d-flex reviews flex-wrap mx-5 my-5 py-5">
        <!--CARD 1-->
        <div class="card col-6">
          <div>
            <img src="@/assets/images/review_1-compressor.jpg" alt="">
          </div>

          <div>
            <p>"The trainers at Avada Gym have helped me reach my fitness goals beyond anything i could of hoped for, i love it"</p>
            <h6>- Tara Smith</h6>
          </div>
          
        </div>
         <!--CARD 2-->
        <div class="card col-6">
          <div>
            <img src="@/assets/images/review_1-compressor.jpg" alt="">
          </div>

          <div>
            <p>"The trainers at Avada Gym have helped me reach my fitness goals beyond anything i could of hoped for, i love it"</p>
            <h6>- Tara Smith</h6>
          </div>
        </div>
         <!--CARD 3-->
        <div class="card col-6">
          <div>
            <img src="@/assets/images/review_1-compressor.jpg" alt="">
          </div>

          <div>
            <p>"The trainers at Avada Gym have helped me reach my fitness goals beyond anything i could of hoped for, i love it"</p>
            <h6>- Tara Smith</h6>
          </div>
        </div>
         <!--CARD 4-->
        <div class="card col-6">
          <div>
            <img src="@/assets/images/review_1-compressor.jpg" alt="">
          </div>

          <div>
            <p>"The trainers at Avada Gym have helped me reach my fitness goals beyond anything i could of hoped for, i love it"</p>
            <h6>- Tara Smith</h6>
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
  background-color: #2e2c2c;
  padding: 0px 150px;
}

h2 {
  color: white;
}

.card {
  padding: 15px ;
  gap:20px;
  background-color: hsla(0, 0%, 12%, 1);
  color: white;
  font-size: 11px;
  display: flex;
  flex-direction: row;
}

</style>
