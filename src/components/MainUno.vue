<template>
    <div class="main">
        <div class="centro-main">
            <div class="testi">
                <h1>Thousands of courses for any type of student</h1>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quo, ab dolores aliquid molestias quis facilis officia iure? Vero quam nulla, voluptatem id enim cum ipsam soluta. Ex neque molestias, alias fugiat optio non eos quaerat exercitationem.</p>
                <button> <span>Broswe through courses</span> </button>
            </div>
            <div class="image">
                
            </div>
            <div class="libri">

            </div>

        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
.main{
    width: 100%;
    height: 70vh;
    background-image: url('/src/assets/img/home-background.png');
    background-size: contain;
    background-repeat: no-repeat;
    display: flex;
    align-items: center;
}
.centro-main{
    width: 62%;
    height: 100%;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
    position: relative;
}
 .image{
    width: 40%;
    height: 50%;
    background-image: url('/src/assets/img/Graduation-Illustration.png');
    background-size: contain;
    background-repeat: no-repeat;
} 
.testi{
    width: 50%;
    height: 60%;
    display: flex;
    flex-direction: column;
    justify-content: space-between;

        h1{
            font-size: 37px;
        }
        button{
            width: max-content;
            padding: 12px 22px 12px 22px;
            border-radius: 20px;
            border-style: none;
            background-color: #E9D758;
                span{
                    font-size: 12px;
      
                    color: #FFFFFF;
                    }
         }
}
.libri{
    position: absolute;
    width: 60px;
    height: 60px;
    top: 20px;
    background-image: url('/src/assets/img/Books-icon.png');
    background-size: contain;
    background-repeat: no-repeat;
}

</style>