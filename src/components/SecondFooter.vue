<template>
<div class="box-footer py-5">
    <div class="container-md pt-5">
        <div class="row">
            <div class="col-3">
                <h6 class="py-3">COME FIND US</h6>
                <p>12345 North Main Street</p>
                <p>New York,NY 555555</p>
                <p>Phone:1.800.555.6789</p>
                <p>Email:info@your-domain.com</p>

            </div>

            <div class="col-3">
                <h6 class="py-3">RECENT POSTS</h6>
                <p class="me-5">&#x276F; Train with free weights or your body weight?</p>
                <hr class="me-5">
                <p class="me-5">&#x276F; Nutritional advice that will keep you training</p>
                <hr class="me-5">
                

            </div>

            <div class="col-3">
                <h6 class="py-3">OPENING TIMES</h6>
                <p>Weekdays Monday-Friday</p>
                <p>09:00 - 19:00</p>
                <p>Weekends Saturday - Sunday</p>
                <p>09:00 - 21:00</p>

            </div>

            <div class="col-3 pt-3">
                
                <img src="@/assets/images/gym_ad-compressor.jpg" alt="">

            </div>
        </div>
    </div>

</div>
</template>

<script>
export default {
name: 'SecondFooter'
}
</script>

<style lang="scss" scoped>
.box-footer {
    background-color: #252a2d;
} p{
    color:#aeafae;
} h6 {
    color:#7a7a7a;
} hr {
    color: #7a7a7a;
}
</style>