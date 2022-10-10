<template>
    <div class="box" >
        
        <div class="d-flex box-navbar justify-content-between" >

            <div class="logo-header" > 
                <img src="@/assets/images/gym_logo_1x.png" alt="logo">
            </div> 
            <div class="d-flex gap-4 navbar-left" > <!--NAVBAR LINK-->
                <div v-for="link in navbartext" :key="link.text" class="navbar" >
                <a href="">{{ link.text }}</a>


                </div>

            </div>
        
        </div>
        <div>


            
        </div>
        <div class="jumbotron pt-2" >
            <div class="box2 pt-5" > <!---BACKGROUND IMG HOME-->
                <img class="pt-2" src="@/assets/images/home-banner.jpg" alt="home-banner">

                    <div class="text-center title pt-5" >
                    <h1 class="pt-3">NO PAIN NO GAIN</h1> <!---MAIN TITLE--->
                    <p>Motivation is what gets you started. Habit is what keeps you going.</p>

                    <button class="btn rounded-0 px-3" >JOIN US TODAY</button>

                </div>


            </div>

            

        </div>
    </div>
    
    
  
</template>

<script>
export default {
name: 'HeaderComponent',
props : {
    navbartext : Array
}
}
</script>

<style lang="scss" scoped>
.box-navbar{
    width: 100%;
    margin: 0 auto;
    padding: 50px 150px;
}
.box {
    height: 550px;
}
.logo-header img {
    width: 80%;
}

a {
    font-size:16px;
    text-decoration: none;
    color: white;
    &:hover {
        color: red;
    }
}
.navbar {
    gap: 5px;
    font-size: 12px;
}

.jumbotron img {
    width: 100%;
    position: absolute;
    z-index: -1;
    top: -50px;
}
.title {
    color:white ;
    position: relative;
    top: 90px;
}
p {
    color: #aeafae;
}
h1 {
    font-size:80px
}
.btn {
    color: #aeafae;
    border: 1px solid #aeafae;
}
// Hover LOGO
.logo-header img:hover {
    cursor: pointer;
}
</style>