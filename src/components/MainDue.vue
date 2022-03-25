<template>
    <div class="main">
        <div class="linee">

            </div>
        <div class="main-centro">
            <div class="titoli">
                <h1>Faculties available at EduPrime</h1>
                <p>A single university with a load of courses, tailored to satisfy any student's needs.</p>
            </div>
            
            <div class="sezioni">
                <div class="img1mod">
                    <div class="immagine"></div>
                    <h4>Law Faculty</h4> 
                </div>
                <div class="img1">
                    <div class="immagine2"></div>
                    <h4>Economy</h4>
                </div>
                <div class="img1">
                    <div class="immagine3"></div>
                    <h4>Medicine</h4>
                </div>
                <div class="img1">
                    <div class="immagine4"></div>
                    <h4>Computer Science</h4>
                </div>
                <div class="img1">
                    <div class="immagine5"></div>
                    <h4>Graphic Design</h4>
                </div>
                <div class="spunta">

                </div>

            </div>
            <div class="info">
                <div class="bg-img">

                </div>
                <div class="titoli-sotto">
                    <h1>Law Faculty</h1>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Obcaecati repudiandae assumenda labore iure porro! Eveniet, pariatur unde optio ipsum minima aliquid praesentium quidem, architecto dolorum maxime voluptatem, id odit similique.</p>
                    <button class="bottone"><span>Read More</span> </button>
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
.linee{
    width: 100%;
    height: 137px;
    border: 1px solid #ECECEE;
    position: absolute;
    top: 137px;
    box-shadow: 0 14px 28px rgba(0,0,0,0.25), 0px 0px 5px 3px rgba(0,0,0,0.22);
}
.main{
    width: 100%;
    height: 90vh;
    position: relative;
}
.main-centro{
    width: 62%;
    height: 100%;
    margin: 0 auto;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}
.titoli{
    width: 100%;
    height: 30%;
    text-align: center;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;

        h1{
            font-size: 37px;
        }
        p{
            width: 360px;
            margin-top: 20px;
        }
}
.sezioni{
    width: 100%;
    height: 30%;
    position: relative;
    display: flex;    
     
}
.img1{
    width: 20%;
    height: 100%;
    border: 1px solid #ECECEE;   
    background-image: url();
    background-size: 70%;
    background-repeat: no-repeat;
    display: flex;
    flex-direction: column;
    justify-content: space-around;
    align-items: center;
        h4{
            color: #E56768;
        }
}
.img1mod{
    width: 20%;
    height: 100%;
    border: 1px solid #ECECEE;   
    border-bottom: none;
    background-image: url();
    background-size: 70%;
    background-repeat: no-repeat;
    display: flex;
    flex-direction: column;
    justify-content: space-around;
    align-items: center;
    background-color: rgba($color: #e21919, $alpha: 0.4);
    
    
        h4{
            color: #FFFFFF;
        }
}
.immagine{
    width: 60%;
    height: 60%;
    
    background-repeat: no-repeat;
    background-size: contain;
    background-image: url('/src/assets/img/Gavel-v2.png');
}
.immagine2{
    width: 60%;
    height: 60%;
    background-image: url('/src/assets/img/Coins-tabs-v2.png');
    background-repeat: no-repeat;
    background-size: contain;
}
.immagine3{
    width: 60%;
    height: 60%;
    background-image: url('/src/assets/img/Medicine-tabs-v2.png');
    background-repeat: no-repeat;
    background-size: contain;
}
.immagine4{
    width: 60%;
    height: 60%;
    background-image: url('/src/assets/img/Computer-tabs-v2.png');
    background-repeat: no-repeat;
    background-size: contain;
}
.immagine5{
    width: 60%;
    height: 60%;
    background-image: url('/src/assets/img/Palette-tabs-v2.png');
    background-repeat: no-repeat;
    background-size: contain;
}
.info{
    width: 100%;
    height: 50%;
    display: flex;
    justify-content: space-between;
    margin-top: 60px;
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
    justify-content: space-around;
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
    background-image: url('/src/assets/img/Gavel-Illustration-e1556884768193.png');
    background-size: contain;
    background-repeat: no-repeat;
}
.spunta {
  width: 0;
  height: 0;
  border-left: 9px solid transparent;
  border-right: 9px solid transparent;
  border-top: 10px solid #e21919;
  opacity: 0.4;
  position: absolute;
  bottom: -9px;
  left: 78px;
}
.bottone{
    box-shadow: 0 14px 28px rgba(0,0,0,0.25), 0 5px 5px rgba(0,0,0,0.22);
}
.bottone:hover{
    background-color: #E56768;
    box-shadow: 0 14px 28px rgba(0,0,0,0.25), 0 5px 5px rgba(0,0,0,0.22);
}
</style>