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
          <div class="nav-dentro"> 
            <span class="span">Home<i class="fa-solid fa-caret-down"></i></span>
            <span class="span">Courses<i class="fa-solid fa-caret-down"></i></span>
            <span >About Us</span>
            <span class="span">News<i class="fa-solid fa-caret-down"></i></span>
            <span class="span">Pages<i class="fa-solid fa-caret-down"></i></span>
            <span >Contact</span>
            <span>Purchase</span>
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
              <button class="bottone">
                <span class="span"><i class="fa-solid fa-magnifying-glass"></i>Search courses</span> 
              </button>
              <button class="bottone2">
                <span  class="span"><i class="fa-solid fa-user-plus"></i>Apply for university</span> 
              </button>
            </div>
          
        </div>
        <!-- bg sotto header -->
        <div class="bg-sotto">

        </div>

      

    </div>

  </div>
  
</template>


<script>

export default {
  
  
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
  height: 80vh;
  background-color: #E56768;
  display: flex;
  flex-direction: column;
  justify-content: space-around;
  position: relative;
}
.bg-header{
  width: 100%;
  height: 100%;
  background-color: #E56768;
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
    span{
      font-size: 12px;
      
      color: #FFFFFF;
    }
}
.bottone2{
  padding: 12px 22px 12px 22px;
  border-radius: 20px;
  border-style: none;
  background-color: #FFFFFF;
  
    span{
      font-size: 12px;
      
      color: #E56768;
    }
}

/* centro head */
.centrohead{
  width: 39%;
  height: 40%;
  border: 1px solid black;
  margin: 0 auto;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: space-around;
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

</style>