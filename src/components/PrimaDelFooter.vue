<template>
    <div class="tutto">
        <div class="sub">
            <!-- subscribe -->
            <div class="sub-dentro">
                <h1>Subscribe Now to Our Newsletter !</h1>
                <input type="text" placeholder="Email address...">
                <div class="puls-gial">
                    <i id="plane" class="fa-solid fa-paper-plane"></i>
                </div>
            </div>
            
        </div>
            <!-- partners -->
        <div class="partners">
            <div class="pt-dentro">
                <div class="scritte">
                    <h1>Partners</h1>
                    <p>Lorem ipsum dolor Accusantium, Lorem ipsum dolor sit amet consectetur, adipisicing elit.</p>
                </div>

                <div class="logo">
                    <div class="size-g1"></div>
                    <div class="size1"></div>
                    <div class="size2"></div>
                    <div class="size-g2"></div>
                    <div class="size3"></div>
                    <div class="size4"></div>
                    <div class="size5"></div>
                    <div class="size-g3"></div>
                </div>
            </div>
            <div class="bg-pt">

            </div>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
.tutto{
    width: 100%;
    height: 90vh;
}
/* subscribe */
.sub{
    width: 100%;
    height: 20%;
    background-color: #e57768;
    margin-top: 60px;
    
}
.sub-dentro{
    width: 62%;
    height: 100%;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
    position: relative;

        h1{
            color: #ffffff;
        }

        input{
            padding: 10px 50px 10px 20px;
            border-radius: 20px;
            border-style: none;
            color: #8b8b8a;
        }
        .puls-gial{
            background-color: #e9d758;
            width: 40px;
            height: 40px;
            border-radius: 40px;
            position: absolute;
            right: -5px;
                #plane{
                    color: white;
                    padding: 13px;
                    font-size: 13px;
                }

        }
}

/* parters */
.partners{
    width: 100%;
    height: 80%;
    
}
.pt-dentro{
    width: 62%;
    height: 50%;
    margin: 0 auto;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}
.scritte{
    width: 500px;
    text-align:center;
    margin: 0 auto;
    padding-top: 15px;
        h1{
            padding: 20px;
            font-size: 37px;
        }
}
.logo{
    width: 100%;
    height: 20%;
    display: flex;
    justify-content: space-between;
}
.size-g1{
    width: 20%;
    height: 100%;
    background-image: url('/src/assets/img/partner-2.png');
    background-size: contain;
    background-repeat: no-repeat;
}
.size-g2{
    width: 20%;
    height: 100%;
    background-image: url('/src/assets/img/partner-5.png');
    background-size: contain;
    background-repeat: no-repeat;
}
.size-g3{
    width: 20%;
    height: 100%;
    background-image: url('/src/assets/img/partner-7.png');
    background-size: contain;
    background-repeat: no-repeat;
}
.size1{
    width: 5%;
    height: 100%;
    background-image: url('/src/assets/img/partner-3.png');
    background-size: contain;
    background-repeat: no-repeat;
}
.size2{
    width: 8%;
    height: 100%;
    background-image: url('/src/assets/img/partner-4.png');
    background-size: contain;
    background-repeat: no-repeat;
}
.size3{
    width: 5%;
    height: 100%;
    background-image: url('/src/assets/img/partner-6.png');
    background-size: contain;
    background-repeat: no-repeat;
}
.size4{
    width: 5%;
    height: 100%;
    background-image: url('/src/assets/img/partner-8.png');
    background-size: contain;
    background-repeat: no-repeat;
}
.size5{
    width: 6%;
    height: 100%;
    background-image: url('/src/assets/img/partner-1.png');
    background-size: contain;
    background-repeat: no-repeat;
}
.bg-pt{
    width: 100%;
    height: 50%;
    background-image: url('/src/assets/img/background-wave3.png');
    background-size: cover;
    background-repeat: no-repeat;
    background-color: rgba($color: #f7f8fa, $alpha: 1.0);
}

</style>