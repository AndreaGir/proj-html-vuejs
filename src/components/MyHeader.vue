<template>
  <div>
    <div class="header">
       <div class="bg-header">
      </div> 
        <!-- barra navigazione -->
        <div class="nav">
          <!-- logo e scritta -->
          <div class="logo-scritta">
            <img src="../assets/img/theme_eduprime_logo.png" alt="">

          </div>
          <!-- nav bar e button -->
          <div class="nav-dentro" > 
            <!-- <span class="span">Home<i class="fa-solid fa-caret-down"></i></span>
            <span class="span">Courses<i class="fa-solid fa-caret-down"></i></span>
            <span >About Us</span>
            <span class="span">News<i class="fa-solid fa-caret-down"></i></span>
            <span class="span">Pages<i class="fa-solid fa-caret-down"></i></span>
            <span >Contact</span>
            <span>Purchase</span> -->
            <span class="span" v-for="(links, i ) in array" :key="i">{{links.link}}<i :class="links.icon"></i></span>
            <button class="bottone"><span>VIEW COURSES</span> </button>
          </div>
        </div>
        <!-- scritte centrali -->
        <div class="centrohead">
            <div class="titolo-centro">
              <h1>Key to your succes</h1>
            </div>
            <div class="p-centro">
              <p>EduPrime is the most versatile WordPress Theme for education purposes, showcasing universities, courses, secondary schools etc.</p>
            </div>
            <div class="bottoni-centro">
              <button class="bottone-search">
                <span class="span"><i class="fa-solid fa-magnifying-glass"></i>Search courses</span> 
              </button>
              <button class="bottone2">
                <span  class="span"><i class="fa-solid fa-user-plus"></i>Apply for university</span> 
              </button>
            </div>
          
        </div>
        <!-- bg sotto header -->
        <div class="bg-sotto">
          <p>Purchase Eduprime on envato Market</p>
          <div class="triangle-down">

        </div>
        </div>

        <div class="puls-laterale">
          <i id="icn" class="fa-solid fa-cart-arrow-down"></i>
          <i id="icn" class="fa-solid fa-book-open"></i>
          <i id="icn" class="fa-regular fa-circle"></i>
        </div>

        


    </div>
    
  </div>
  
</template>


<script>

export default {

  data(){
    return{
      array: [
      {
        link: 'Home',
        icon: 'fa-solid fa-caret-down'
      },
      {
        link: 'Courses',
        icon: 'fa-solid fa-caret-down'
      },
      {
        link: 'About us',
        active: false
      },
      {
        link: 'News',
        icon: 'fa-solid fa-caret-down'
      },
      {
        link: 'Pages',
        icon: 'fa-solid fa-caret-down'
      },
      {
        link: 'Contact',
        active: false
      },
      {
        link: 'Purchase',
        active: false
      }
    ]
    }
    

  }
   
    
  
  
}
</script>


<style lang="scss" scoped>
*{
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
.header{
  width: 100%;
  height: 90vh;
  background-color: #E56768;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  
  position: relative;
}
.bg-header{
  width: 100%;
  height: 100%;
  background-color:rgba(228, 6, 6, 0.767);
  background-image: url('/src/assets/img/theme_slider2_bg-1.jpg');
  opacity: 0.2;
  background-repeat: no-repeat;
  background-size: cover;
  position: absolute;
}
/* nav */
.nav{
  width: 94%;
  height: 16%;
  margin: 0 auto;
  background-color: transparent;
  display: flex;
  justify-content: space-between;
}
.logo-scritta{
  width: 20%;
  height: 100%;
  display: flex;
  align-items: center;
  
  
    img{
      width: 100%;
      opacity: none;
      z-index: 999;
    }
}
.nav-dentro{
  width: 60%;
  height: 100%;
  display: flex;
  justify-content: space-around;
  align-items: center;
  color: #FFFFFF;
  
  
}
.span {
  display: flex;
  gap: 5px;
}
.bottone{
  padding: 12px 22px 12px 22px;
  border-radius: 20px;
  border-style: none;
  background-color: #E9D758;
  box-shadow: 0 14px 28px rgba(0,0,0,0.25), 0 5px 5px rgba(0,0,0,0.22);
    span{
      font-size: 12px;
      
      color: #FFFFFF;
    }
}
/* centro head */
.bottone2{
  padding: 12px 22px 12px 22px;
  border-radius: 20px;
  border-style: none;
  background-color: rgba(255, 255, 255 , 1.0 );
  box-shadow: 0 14px 28px rgba(0,0,0,0.25), 0 5px 5px rgba(0,0,0,0.22);
  
  right: 80px;
  
  
    span{
      font-size: 12px;
      
      color: #E56768;
    }
}
.bottone-search{
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

.centrohead{
  width: 39%;
  height: 40%;

  margin: 0 auto;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: space-around;
  position: relative;
}
.titolo-centro > h1{
  color: #FFFFFF;
}
.p-centro > p{
  text-align: center;
  color: #FFFFFF;
}
.bottoni-centro{
  display: flex;
  gap: 25px;
}
.bg-sotto{
  width: 100%;
  height: 17vh;
  background-image: url('/src/assets/img/Wave-1.png');
  /* background-color: #E56768; */
  opacity: 1;
  bottom: -80px;
    p{
      width: 200px;
      border: 1px solid black;
      text-align: center;
      background-color: #000000;
      color: #FFFFFF;
      font-size: 12px;
      position: absolute;
      bottom: 10px;
      left: 40px;
      border-radius: 5px;
    }
}
.puls-laterale{
  position: absolute;
  width: 30px;
  height: 70px;
  background-color: #E9D758;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  bottom: 50%;
  border-radius: 3px;
  gap: 4px;
  box-shadow: 0 14px 28px rgba(0,0,0,0.25), 0 5px 5px rgba(0,0,0,0.22);
}
#icn{
  color: #FFFFFF;
}
.triangle-down {
  width: 0;
  height: 0;
  border-left: 5px solid transparent;
  border-right: 5px solid transparent;
  border-top: 10px solid #000000;
  position: absolute;
  bottom: 0;
  left: 138px;
}

</style>