<template>
    <div class="tutto">
        <div class="tutto-dentro">
            <div class="latest">
                <h1>Latest Courses</h1>
                <div class="courses">
                    <div class="make">
                        <div class="image">

                        </div>
                        <h3>Coaching Session</h3>
                        <p><i id="icon" class="fa-solid fa-user"></i>Teacher: James Colins</p>
                        <p><i id="icon" class="fa-solid fa-money-bill"></i>Price: $21.00</p>
                        <div class="plus">
                            <h5><i id="icon" class="fa-regular fa-eye"></i>View course</h5>
                        </div>
                    </div>
                    <div class="make">
                        <div class="image2">

                        </div>
                        <h3>How to be a speaker</h3>
                        <p><i id="icon" class="fa-solid fa-user"></i>Teacher: James Colins</p>
                        <p><i id="icon" class="fa-solid fa-money-bill"></i>Price: Free</p>
                        <div class="plus">
                            <h5><i id="icon" class="fa-regular fa-eye"></i>View course</h5>
                        </div>
                    </div>
                    <div class="make">
                        <div class="image3">

                        </div>
                        <h3>Network Introductions</h3>
                        <p><i id="icon" class="fa-solid fa-user"></i>Teacher: James Colins</p>
                        <p><i id="icon" class="fa-solid fa-money-bill"></i>Price: Free</p>
                        <div class="plus">
                            <h5><i id="icon" class="fa-regular fa-eye"></i>View course</h5>
                        </div>
                    </div>
                    <div class="make">
                        <div class="image4">

                        </div>
                        <h3>Brand Managment</h3>
                        <p><i id="icon" class="fa-solid fa-user"></i>Teacher: James Colins</p>
                        <p><i id="icon" class="fa-solid fa-money-bill"></i>Price: Free</p>
                        <div class="plus">
                            <h5><i id="icon" class="fa-regular fa-eye"></i>View course</h5>
                        </div>
                    </div>
                </div>

            </div>
            <div class="discover">
                 <div class="info1">
                    
                    <div class="titoli-sotto1">
                        <div class="icona-text1">

                        </div>
                         <h1>The most efficient examination method</h1>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Obcaecati repudiandae assumenda labore iure porro! Eveniet, pariatur unde optio ipsum minima aliquid praesentium quidem, architecto dolorum maxime voluptatem, id odit similique.</p>
                        <button class="bottone1"><span>Discover the Method</span> </button>
                    </div>
                    <div class="bg-img1">

                    </div>
                </div>
                
            </div>

            <div class="list">
                <div class="info">
                    <div class="bg-img">

                    </div>
                    <div class="titoli-sotto">
                        <div class="icona-text">

                        </div>
                         <h1>Variable fees for international students</h1>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Obcaecati repudiandae assumenda labore iure porro! Eveniet, pariatur unde optio ipsum minima aliquid praesentium quidem, architecto dolorum maxime voluptatem, id odit similique.</p>
                        <button class="bottone"><span>List of Fees</span> </button>
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
    height: 170vh;
    margin-top: 20%;
}
.tutto-dentro{
    width: 62%;
    height: 100%;
    margin: 0 auto;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}
/* latest */
.latest{
    width: 100%;
    height: 30%;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}
.courses{
    display: flex;
    justify-content: space-between;
}
.make{
    width: 24%;
    height: 200px;
    text-align: center;
    background-color: #ffffff;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    gap: 7px;
    border: 1px solid #8b8b8a;
    border-radius: 8px;
    position: relative;

        h3{
            font-size: 15px;
        }

        p{
            font-size: 13px;
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
.image{
    width: 60px;
    height: 60px;
    margin-bottom: 7px;
    background-image: url('/src/assets/img/Decisions-icon.png');
    background-size: cover;
}
.image2{
    width: 60px;
    height: 60px;
    margin-bottom: 7px;
    background-image: url('/src/assets/img/Speaker-icon.png');
    background-size: cover;
}
.image3{
    width: 60px;
    height: 60px;
    margin-bottom: 7px;
    background-image: url('/src/assets/img/Network-icon.png');
    background-size: cover;
}
.image4{
    width: 60px;
    height: 60px;
    margin-bottom: 7px;
    background-image: url('/src/assets/img/Brand-icon.png');
    background-size: cover;
}

/* discover */
.discover{
    width: 100%;
    height: 30%;
    display: flex;
    justify-content: space-between;
}
.info1{
    width: 100%;
    height: 100%;
    display: flex;
    justify-content: space-between;
}
.bg-img1{
    width: 50%;
    height: 100%;
}
.titoli-sotto1{
    width: 50%;
    height: 100%;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
        h1{
            margin-bottom: 29px;
        }
        p{
            padding-bottom: 29px;
        }
   
    .bottone1{
        width: max-content;
        padding: 12px 22px 12px 22px;
        border-radius: 20px;
        border-style: none;
        background-color: #E56768;
                span{
                    font-size: 12px;
      
                    color: #FFFFFF;
    }
}
}
.bg-img1{
    width: 40%;
    height: 100%;
    background-image: url('/src/assets/img/Exam-Illustration.png');
    background-size: contain;
    background-repeat: no-repeat;
    margin-top: 40px;
}
.icona-text1{
    width: 20%;
    height: 50px;
    background-image: url('/src/assets/img/Exam-icon.png');
    background-size: contain;
    background-repeat: no-repeat; 
    margin-bottom: 10px;
}


/* list */
.list{
    width: 100%;
    height: 30%;
    display: flex;
    justify-content: space-between;
}
.info{
    width: 100%;
    height: 100%;
    display: flex;
    justify-content: space-between;
}
.bg-img{
    width: 50%;
    height: 100%;
}
.titoli-sotto{
    width: 50%;
    height: 100%;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
        h1{
            margin-bottom: 29px;
        }
        p{
            padding-bottom: 29px;
        }
   
    .bottone{
        width: max-content;
        padding: 12px 22px 12px 22px;
        border-radius: 20px;
        border-style: none;
        background-color: #E56768;
                span{
                    font-size: 12px;
      
                    color: #FFFFFF;
    }
}
}
.bg-img{
    width: 40%;
    height: 100%;
    background-image: url('/src/assets/img/Girl-Illustration.png');
    background-size: contain;
    background-repeat: no-repeat;
    margin-top: 40px;
}
.icona-text{
    width: 20%;
    height: 50px;
    background-image: url('/src/assets/img/Exam-icon-1.png');
    background-size: contain;
    background-repeat: no-repeat; 
    margin-bottom: 10px;
}
</style>