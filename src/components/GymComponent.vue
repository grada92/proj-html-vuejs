<template>
  <div class="box-gym py-5">
    <div class="container-md py-5 text-center">
      <h2>HIGH PERFORMANCE FACILITIES</h2>

      <img src="@/assets/images/divider-xx-red.png" alt="divider-xx">

      <div class="row pt-5">
        <div class="col-4"> <!--Card 1-->
          <img src="@/assets/images/home-image1.jpg" alt="image1">

        </div>

        <div class="col-4"> <!--Card 2-->
          <img src="@/assets/images/home-image2.jpg" alt="image2">

        </div>

        <div class="col-4"> <!--Card 3-->
          <img src="@/assets/images/home-image3.jpg" alt="image3">

        </div>

      </div>

      <div class="row py-5">
        <div class="col-4"> <!--Card 4-->
          <img src="@/assets/images/home-image4.jpg" alt="image4">

        </div>

        <div class="col-4"> <!--Card 5-->
          <img src="@/assets/images/home-image54.jpg" alt="image5">

        </div>

        <div class="col-4"> <!--Card 6-->
          <img src="@/assets/images/home-image6.jpg" alt="image6">

        </div>

      </div>

    </div>
    <div class="box-text pt-5">
      <!--Add Background Image-->
      <div class="box-img">  
        <div class="row">

          <div class="col-12 text-center">
            <div class="title">
              <!---Add Title--->
              <h2>"I fear not the man who has practiced 10,000 kicks once , but i fear the man who has practiced one kick 10,000 times"</h2>
              <img src="@/assets/images/divider-white-xx.png" alt="divider-xx-white">
              <h5>BRUCE LEE &#8226; QUOTE OF THE DAY</h5>
            </div>
            
          </div>
        </div>

      </div>

    </div>

  </div>

    
</template>

<script>
export default {
name: 'GymComponent'
}
</script>

<style lang="scss" scoped>
.box-gym {
  background-color: #212425;
  h2 {
    line-height: 50px;
    color: white;
  }
  h5 {
    padding-top: 30px;
  }
}

.title {
  padding: 100px 420px; 
  color:white
}
.box-img {
  background-image: url(@/assets/images/home-testimonial-bg.jpg);
  height: 550px;
  background-size: cover;
  background-position: 0px -300px;
}
</style>