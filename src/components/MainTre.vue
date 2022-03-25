<template>
    <div class="tutto">
        <div class="bg-up">

        </div>
        <div class="tutto-sotto">
            <div class="uni">
                <div class="title">
                    <div class="icon">

                    </div>
                    <div class="titolo">
                        <h1>University Year</h1>
                    </div>
                </div>
                <div class="time-line">
                    <div class="info">
                        <h3>Demo Classes</h3>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusamus praesentium facere.</p>
                    </div>
                    <div class="info2">
                        <h3>Graduation Day</h3>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusamus praesentium facere.</p>
                    </div>
                     <div class="info3">
                        <h3>Orientation</h3>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusamus praesentium facere.</p>
                    </div>
                    <div class="info4">
                        <h3>Evalutation</h3>
                       <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusamus praesentium facere.</p>
                    </div> 
                </div>

            </div>
            <div class="upco">

                <div class="event">
                    <div class="eve-lg"></div>
                    <h1>Upcoming Events</h1>
                </div>

                <div class="calendario-eventi">
                    <div class="cal-1">
                        <h3>Coaching Session</h3>
                        <p><i id="icon" class="fa-regular fa-calendar-days"></i>24 Mar 18:00 PM</p>
                        <p>Lorem ipsum dolor sit amet sed. Exercitationem quos praesentium[...]</p>
                        <div class="plus">
                            <h5>+ Find More</h5>
                        </div>
                    </div>
                     <div class="cal-1">
                        <h3>Coaching Session</h3>
                        <p><i id="icon" class="fa-regular fa-calendar-days"></i>30 Mar 20:00 PM</p>
                        <p>Lorem ipsum dolor sit amet sed. Exercitationem quos praesentium[...]</p>
                        <div class="plus">
                            <h5>+ Find More</h5>
                        </div>
                    </div>
                     <div class="cal-1">
                        <h3>Coaching Session</h3>
                        <p><i id="icon" class="fa-regular fa-calendar-days"></i>1 Apr 15:00 PM</p>
                        <p>Lorem ipsum dolor sit amet sed. Exercitationem quos praesentium[...]</p>
                        <div class="plus">
                            <h5>+ Find More</h5>
                        </div>
                    </div>
                    
                </div>
                

                <button class="bottone"> <span>View All Events</span> </button>
            </div>
        </div>
        <div class="bg-down">

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
    height: 140vh;
    
}
.tutto-sotto{
    width: 100%;
    height: 100%;
    background-color: #E56768;
}
.bg-up{
    width: 100%;
    height: 20%;
    background-image: url('/src/assets/svg/svg-0.svg');
    background-size: cover;
}
.bg-down{
    width: 100%;
    height: 9%;
    background-image: url('/src/assets/svg/svg-1.svg');
    background-size: cover;
}
/* uni */
.uni{
    width: 62%;
    height: 50%;
    margin: 0 auto;
}
.title{
    width: 50%;
    height: 20%;
    margin: 0 auto;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
}
.titolo{
    font-size: 16px;
    color: #ffffff;
    background-color: rgb(255, 0, 0);
}
.icon{
    width: 12%;
    height: 50%;
    background-image: url('/src/assets/img/Clock-and-Bell.png');
    background-size: contain;
    background-repeat: no-repeat;
}
.time-line{
    width: 100%;
    height: 100%;
    background-position: 30px;
    background-image: url('/src/assets/img/Timeline-Item.png');
    background-size: contain;
    background-repeat: no-repeat;
    position: relative;
}
.info{
    position: absolute;
    width: 300px;
    text-align: center;
    top: 80px;
    left: 210px;
        h3{
            font-size: 17px;
            color: white;
        }
        p{
            font-size: 14px;
            color: #ffffffcc;
            padding-top: 5px;
        }
}
.info2{
    position: absolute;
    width: 300px;
    text-align: center;
    top: 80px;
    left: 549px;
        h3{
            font-size: 17px;
            color: white;
        }
        p{
            font-size: 14px;
            color: #ffffffcc;
            padding-top: 5px;
        }
}
.info3{
    position: absolute;
    width: 300px;
    text-align: center;
    bottom: 80px;
    left: 42px;
        h3{
            font-size: 17px;
            color: white;
        }
        p{
            font-size: 14px;
            color: #ffffffcc;
            padding-top: 5px;
        }
}
.info4{
    position: absolute;
    width: 300px;
    text-align: center;
    bottom: 80px;
    right: 148px;
        h3{
            font-size: 17px;
            color: white;
        }
        p{
            font-size: 14px;
            color: #ffffffcc;
            padding-top: 5px;
        }
}
/* up.co */
.upco{
    width: 62%;
    height: 50%;
    margin: 0 auto;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: space-around;
} 
.event{
    display: flex;
    flex-direction: column;
    align-items: center;
    padding-top: 30px;
        h1{
            font-size: 32px;
            color: #ffffff;
        }
}
.eve-lg{
    width: 20%;
    height: 50px;
    background-image: url('/src/assets/img/upcoming-events-calendar-icon.png');
    background-size: contain;
    background-repeat: no-repeat; 
   
}
.calendario-eventi{
    width: 100%;
    display: flex;
    justify-content: space-between;
}
.cal-1{
    width: 32%;
    height: 130px;
    text-align: center;
    background-color: #ffffff;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    gap: 7px;
    border-radius: 8px;
    position: relative;

        p{
            font-size: 14px;
            color: #8b8b8a;
        }
        
}
#icon{
    padding-right: 4px;
}
.plus{
    position: absolute;
    bottom: -16px;
        h5{
            background-color: #eb0000e6;
            padding: 8px;
            border-radius: 15px;
            color: #ffffff;
        }
}
.bottone{
  padding: 12px 22px 12px 22px;
  border-radius: 20px;
  border-style: none;
  background-color: #E9D758;
  box-shadow: 0 14px 28px rgba(0,0,0,0.25), 0 5px 5px rgba(0,0,0,0.22);
  left: 100px;
    span{
      font-size: 12px;
      
      color: #FFFFFF;
    }
}
.bottone:hover{
    background-color: #E56768;
    box-shadow: 0 14px 28px rgba(0,0,0,0.25), 0 5px 5px rgba(0,0,0,0.22);
}

</style>