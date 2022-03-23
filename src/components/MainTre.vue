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
                <div class="event-lg">
                    <div></div>
                    <h1>Upcoming Events</h1>
                </div>
                <div>

                </div>
                <div>

                </div>
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
    height: 100px;
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
    border: 1px solid black;
} 

</style>