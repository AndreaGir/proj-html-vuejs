<template>
    <div class="tutto">
        <!-- messaggi e spunta gialla up "absolute"-->
            <div class="mes-1">
                <div class="beg-img">

                </div>
                <p>Purchase Theme</p>
            </div>
            <div class="mes-2">
                <div class="beg-img">

                </div>
                <p>Related Theme</p>

            </div>
            <div class="icona-up">
                <i id="ico-d" class="fa-solid fa-angle-up"></i>
            </div>
            <!-- messaggi e spunta gialla up -->
        <div class="tutto-dentro">
            

            <div class="social">
                <div class="logo">

                </div>
                <div class="scritte">
                    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ipsum hic architecto magnam nisi officia amet illo culpa. Tenetur, nihil officia.</p>
                </div>
                <div class="link-social">
                    <div class="soci"><i id="icon1" class="fa-brands fa-facebook-f"></i></div>
                    <div class="soci"><i id="icon" class="fa-brands fa-twitter"></i></div>
                    <div class="soci"><i id="icon" class="fa-brands fa-instagram"></i></div>
                </div>

            </div>

            <div class="link">
                <div class="get">
                    <h4>Get EduPrime</h4>
                    <p>Request a website</p>
                    <p>Broswe Themes</p>
                    <p>Payment option</p>
                    <p>Support Sistem</p>
                    <p>Checkout</p>
                    <p>Purchase Theme</p>
                </div>
                <div class="net">
                    <h4>Networking</h4>
                    <p>Purchase Theme</p>
                    <p>Our Benefits</p>
                    <p>Our Team</p>
                    <p>Our services</p>
                    <p>Other products</p>
                    <p>My account</p>

                </div>
            </div>

            <div class="search">
                <div class="inp">
                    <input type="text" placeholder="Search ...">
                    <div class="puls-gial">
                    <i id="plane" class="fa-solid fa-paper-plane"></i>
                </div>
                </div>
                <div class="but">
                    <div class="title-s">
                        <h4>Search categories</h4>
                    </div>
                    <div class="butt-s"> 
                        <div class="p-1">
                            <p>ECONOMY</p>
                            <p>DESIGN</p>
                            <p>COACHING</p>
                        </div>
                        
                        <div class="p-2">
                            <p>BUSINESS</p>
                            <p>MEDICINE</p>
                            <p>LAW</p>
                            <p>FITNESS</p>
                        </div>
                        
                    </div>
                    <div class="tit-p">
                        <p>ModelTheme. All rights reserved.</p>
                    </div>
                </div>
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
    height: 70vh;
    background-color: #e56768;
    display: flex;
    align-items: center;
    justify-content: center;
    position: relative;
}
.tutto-dentro{
    
    width: 62%;
    height: 54%;
    display: flex;
    justify-content: space-between;
}
/* social */
.social{
    width: 30%;
    height: 100%;
    
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}
.logo{
    width: 80%;
    height: 60px;
    
    background-image:  url('/src/assets/img/theme_eduprime_logo.png');
    background-size: contain;
    background-repeat: no-repeat;
}
.scritte{
    width: 100%;
    height: 28%;
    
        p{
            font-size: 14px;
            color: #ffffff;
        }
}
#icon{
    color: #ffffff;
    padding: 9px;
}
#icon1{
    color: #ffffff;
    padding: 9px 9px 9px 11px;
}
.link-social{
    width: 80%;
    height: 20%;
   
    display: flex;
    align-items: center;
    gap: 10px;
        .soci{
            width: 35px;
            height: 35px;
            border: 1px solid yellow;
            border-radius: 20px;
        }
}
/* link */
.link{
    width: 33%;
    height: 100%;
    
    display: flex;
    justify-content: space-between;
        .get{
            width: 44%;
            height: 100%;
            
                h4{
                    color: #ffffff;
                    padding-bottom: 20px;
                    font-size: 17px;
                }
                p{
                    color: #ffffff;
                    padding: 10px 0px 0px 0px;
                    font-size: 14px;
                }
        }
        .net{
            width: 44%;
            height: 100%;
                h4{
                    color: #ffffff;
                    padding-bottom: 20px;
                    font-size: 17px;
                }
                p{
                    color: #ffffff;
                    padding: 10px 0px 0px 0px;
                    font-size: 14px;
                }
        }
}
/* search */
.search{
    width: 30%;
    height: 100%;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}
.inp{
    width: 100%;
    height: 30%;
    position: relative;
        input{
            padding: 10px 50px 10px 20px;
            border-radius: 20px;
            border-style: none;
            color: #8b8b8a;
        }
        .puls-gial{
            background-color: #e9d758;
            width: 38px;
            height: 38px;
            border-radius: 40px;
            position: absolute;
            right: -2px;
            top: -2px;
                #plane{
                    color: white;
                    padding: 13px;
                    font-size: 13px;
                }

        }
}
.but{
    max-width: 100%;
    height: 55%;
    display: flex;
    flex-direction: column;
    align-items: flex-end;
    justify-content: space-between;
}
.butt-s{
    max-width: 240px;
    display: flex;
    flex-direction: column;
    p{
        width: 100%;
        font-size: 12px;
        border: 1px solid white;
        color: white;
        width: max-content;
        padding: 4px;
        border-radius: 10px;
    }
}
.p-1{
    display: flex;
    align-items: flex-end;
    justify-content: flex-end;
    gap: 3px;
    padding-bottom: 5px;
}
.p-2{
display: flex;
align-items: flex-end;
justify-content: flex-end;
gap: 3px;
}
.tit-p{
    font-size: 14px;
    color: yellow;
}
.title-s{
    color: white;
}
.mes-1{
    position: absolute;
    left: 40px;
    width: 130px;
    bottom: 60px;
    height: 30px;
    background-color: #8b8b8a;
    display: flex;
    align-items: center;
    padding: 5px;
    border-radius: 7px;
    
        .beg-img{
            width: 18%;
            height: 70%;
            background-image:  url('/src/assets/svg/svg-3.svg');
            background-size: contain;
            background-repeat: no-repeat;
            margin-left: 4px;
        }
        p{
            font-size: 11px;
        
        }
}
.mes-2{
    position: absolute;
    left: 40px;
    bottom: 20px;
    width: 130px;
    height: 30px;
    background-color: #8b8b8a;
    display: flex;
    align-items: center;
    padding: 5px;
    border-radius: 7px;
    
        .beg-img{
            width: 18%;
            height: 70%;
            background-image:  url('/src/assets/svg/svg-2.svg');
            background-size: contain;
            background-repeat: no-repeat;
            margin-left: 4px;
        }
        p{
            font-size: 11px;
        
        }
}
.icona-up{
    position: absolute;
    background-color: #e9d758;
    width: 28px;
    height: 28px;
    border-radius: 40px;
    bottom: 20px;
    right: 30px;
        #ico-d{
            color: white;
            padding: 6px;
            margin-left: 2px;
        }
}


</style>