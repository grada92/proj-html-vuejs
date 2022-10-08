<template>
<div class="second-footer pb-2">
    <div class="box-footer">
        <div class="container-md py-5">
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
    
    <div class="box-second-footer container-md py-4">
        <div class="row">
            <div class="col-8">
                <a class="pe-4" href="#">Copyright 2012-2020</a> <span>|</span>
                <a class="pe-4" href="#">Avada Theme by Theme Fusion</a><span>|</span>
                <a class="pe-4" href="#">All Rights Reserved</a><span>|</span>
                <a class="pe-4" href="#">Powered by Wordpress</a>
            </div>

            <div class="col-4">
                <div class="social-footer d-flex gap-2 px-5">
                    <!---Social Icon-->
                    <div class="fb text-white">
                    <i class="fa-brands fa-facebook-f"></i>
                    </div>

                    <div class="tw text-white">
                    <i class="fa-brands fa-twitter"></i>
                    </div>

                    <div class="ig text-white">
                    <i class="fa-brands fa-instagram"></i>
                    </div>

                </div>
            </div>
        </div>
        


        </div>
        <div class="container-fluid">
            <div class="row me-5">
            <div class="col-12 text-end me-5">
                <button> <i class="fa-solid fa-angle-up"></i></button>
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
.second-footer {
    background-color: #212425;
}
a {
    text-decoration: none;
    color:#aeafae;
    font-size: 13px;
}
span {
    color:#aeafae;
    padding-right: 20px;
}
.social-footer {
    margin-left: 210px;
}
.fb {
  background-color:  #d3615e;
  padding: 5px 12px;
}

.tw {
  background-color:  #d3615e;
  padding: 5px 9px;
}

.ig {
  background-color:  #d3615e;
  padding: 5px 11px;
}
button {
    background-color: #2e3539;
    color: white;
    padding: 3px 14px;
    border: none;
    border-radius: 3px;
}

</style>