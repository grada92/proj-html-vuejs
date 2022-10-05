<template>
    <div class="box" >

        <div class="d-flex justify-content-between container" >

        <div class="logo-header" >
            <img src="@/assets/images/gym_logo_1x.png" alt="logo">
        </div> 

        <div v-for="link in navbartext" :key="link.text" class="navbar" >
        {{ link.text }}


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
    padding: 10px;
}

.logo-header img {
    width: 80%;
}
.box {
    background-color: #252a2b;
}

.navbar {
    gap: 5px;
    font-size: 12px;
    color: white;
}


</style>