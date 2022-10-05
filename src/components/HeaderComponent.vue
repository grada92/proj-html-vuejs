<template>
    <div class="box" >
        
        <div class="d-flex justify-content-between container" >

            <div class="logo-header" >
                <img src="@/assets/images/gym_logo_1x.png" alt="logo">
            </div> 
            <div class="d-flex gap-4 navbar-left" >
                <div v-for="link in navbartext" :key="link.text" class="navbar" >
                <a href="">{{ link.text }}</a>


                </div>

            </div>
        
        </div>
        <div>


            
        </div>
        <div class="jumbotron" >
            <div class="box2" >
                <img src="@/assets/images/home-banner.jpg" alt="home-banner">

                    <div class="text-center title my-5" >
                    <h1>NO PAIN NO GAIN</h1>
                    <p>Motivation is what gets you started. Habit is what keeps you going.</p>

                    <button class="btn" >JOIN US TODAY</button>

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
.container {
    width: 1200px;
    margin: 0 auto;
    padding: 20px 0px;
    
}

.logo-header img {
    width: 80%;
}

a {
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
    top: 0;
    background-size: cover;
}
.title {
    color:white ;
    position: relative;
    top: 90px;
}
h1 {
    font-size:80px
}
.btn {
    color: white;
    border: 1px solid white;
}

</style>