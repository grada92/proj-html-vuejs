<template>
  <div class="box-service container-fluid">
    <div class="d-flex box-card row justify-content-center mx-5 gx-3">
      <div class="d-flex card-service mx-5">


        <!---CARD 1-->
        <div class="d-flex align-items-center  card bg-transparent text-center">
          <i id="border" class="fs-4 text-danger fa-solid fa-link"></i> <!--ADD ICON--->
          <h5 class="fs-6">Strength & Conditioning</h5>

          <img src="@/assets/images/divider-x-red.png" alt="">

        

          <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ipsam, rem!</p>

        </div>

        <!---CARD 2-->
        <div class="card align-items-center bg-transparent text-center">
          <i id="border" class="fs-4 text-danger fa-solid fa-bicycle"></i><!--ADD ICON--->
          <h5 class="fs-6">Fitness & Cardio</h5>

          <img src="@/assets/images/divider-x-red.png" alt="">

        

          <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ipsam, rem!</p>

        </div>
        <!---CARD 3-->
        <div class="card align-items-center bg-transparent text-center">
          <i id="border" class="fs-4 text-danger fa-solid fa-cloud"></i><!--ADD ICON--->
          <h5 class="fs-6">Flexibility & Rest</h5>

          <img src="@/assets/images/divider-x-red.png" alt="">

        

          <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ipsam, rem!</p>

        </div>
        <!---CARD 4-->
      <div class="card  align-items-center bg-transparent text-center">
        <i id="border" class="fs-4 text-danger fa-solid fa-heart-pulse"></i><!--ADD ICON--->
        <h5 class="fs-6">Health & Diet</h5>

        <img src="@/assets/images/divider-x-red.png" alt="">
        

        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ipsam, rem!</p>

      </div>


      </div>
      


    </div>


  </div>
</template>

<script>
export default {
name: 'ServiceComponent'
}
</script>

<style lang="scss" scoped>
.box-service {
  background-image: url(@/assets/images/gym_bkgd_bw-compressor.jpg);
  background-size: contain;
  max-width: 100%;
  padding: 80px 100px;
}
.card {
  color:white;
  margin: 70px;
  gap:20px;
  padding: 15px;
  color: none;
  margin: 0px 20px;
}

p {
  font-size: 12px;
  color: #6b6b6b;
}

img {
  height: 10px;
  width: 10px;
 
}

#border {
  border-radius: 100%;
  border: 2px solid red;
  padding: 20px;
}

</style>