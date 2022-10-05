<template>
  <div class="box-service">

    <div class="d-flex box-card">

      <div class="card bg-transparent text-center">
        <i class="text-danger fa-solid fa-link"></i>
        <h5>Strength & Conditioning</h5>

        

        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ipsam, rem!</p>

      </div>
      <div class="card bg-transparent text-center">
        <i class="text-danger fa-solid fa-bicycle"></i>
        <h5>Strength & Conditioning</h5>

        

        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ipsam, rem!</p>

      </div>

      <div class="card bg-transparent text-center">
        <i class="text-danger fa-solid fa-cloud"></i>
        <h5>Strength & Conditioning</h5>

        

        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ipsam, rem!</p>

      </div>

      <div class="card  bg-transparent text-center">
        <i class="text-danger fa-solid fa-heart-pulse"></i>
        <h5>Strength & Conditioning</h5>

        

        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ipsam, rem!</p>

      </div>


    </div>


  </div>
</template>

<script>
export default {
name: 'ServiceComponent'
}
</script>

<style lang="scss" scooped>
.box-service {
  background-image: url(@/assets/images/gym_bkgd_bw-compressor.jpg);
  background-size: contain;
}
.card {
  color:white;
  margin: 70px;
  gap:20px;
  padding: 15px;
  color: none;
}


</style>