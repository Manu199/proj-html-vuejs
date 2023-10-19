<script>
export default {
    name: 'Header'
}
</script>


<template>
 
 <header>

    <div class="header-content">
     
        <div class="header-container">
            
            <div class="logo">
                <img src="../../public/Logo.jpg" alt="">
                </div>
                
                <div class="nav">
                    <nav> 
                        <a href="">Home</a>
                        <a href="">About</a>
                        <a href="">Academics</a>
                        <a href="">Courses</a>
                        <a href="">News</a>
                    </nav>
                </div>
                
            </div>
            

                <img class="jumbs" src="../../public/img/02_Landing-Page.jpg" alt="">

                <div class="content-img">
                    <h1>Professional development for coaches and leaders</h1>
                    <button>Learn More</button>
                </div>


    </div>
 </header>

</template>


<style scoped lang="scss">

    @use '../scss/main.scss';

header {
    width: 100%;
    .header-content{

        position: relative;
        z-index: 9;
        height: 100%;
        width: 100%;
        // overflow: hidden;
        .jumbs{
            height: 100%;
            position: relative;
            top: -75px;
            width: 100%;

            img{ 
                position: absolute;
                top: 0;
            }
        }
    }
    .content-img{
        position: absolute;
        top: 40%;
        left: 50%;
        transform: translate(-50%, -50%);

        h1{
            font-family: 'PT Serif', serif;
            font-size: 3.5vw;
            font-weight: 100;
            text-transform: capitalize;
            text-align: center;
            color: $dark-text;
        }
    }
}

.header-container {
    width: calc(100% - 18px);
    height: 75px;
    display: flex;
    align-items: center;
    justify-content: space-around;
    background-color: white;
    position: relative;
    z-index: 1;
    img {
        width: 151px;
        margin-top: 44px;
        margin-left: 30%;
        z-index: 99;
        position: relative;
    }

    div.nav{
        margin-right: 100px;
    }

    nav {
        list-style: none;
        
        a {
        margin: 20px;
        text-decoration: none;
        color: black;
        font-weight: 600;
        text-align: center;
        }
    }
}

</style>