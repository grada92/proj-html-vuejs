<template>
  <div class="box-footer d-flex ">
    <div class="container-fluid">
      <div class="row img-footer align-items-center text-center">
        <div class="col-8 box-text text-center" >
          <h2>Achieve Your Fitness Goals</h2>
          <p class="text-white">Flexible membership package to suit all levels of athlete and achive your fitness goals</p>
        </div>

        <div class="col-3">
          <!--BUTTON SIGN UP-->
          <button class="btn rounded-0 me-5" >JOIN US</button> 
        
        </div>

      </div>

    </div>

    
  </div>

</template>

<script>
export default {
name: 'FooterComponent'
}
</script>

<style lang="scss" scoped>
.box-footer {
  background-color: #2b2b2b;
}

.img-footer {
  background-image: url(@/assets/images/home-parallax.jpg);
  height: 200px;
  background-position: 0px -200px;
}

.btn{
  color: white;
  border: 1px solid white;
}
p {
  margin: 0px 0px 0px -25px;
}
h2 {
  margin: 0px 0px 0px -240px;
  color: white;
}
</style>