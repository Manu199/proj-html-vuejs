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
    @use '../scss/partials/variables';

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
        justify-content: center;
        align-items: center;
        display: flex;
        flex-direction: column;

        h1{
            font-family: 'Playfair Display', serif;
            font-size: 3vw;
            font-weight: 100;
            text-transform: capitalize;
            text-align: center;
            color: #192836;
            margin-top: -25px;
        }

        button{
            padding: 17px 40px;
            background-color: transparent;
            color: #495057;
            border: 1px solid #00000061;
            font-family: sans-serif;
            font-size: small;
            font-weight: 600;
            letter-spacing: 2px;
            margin-top: 50px;

            &:hover{
                background-color: #D74d52;
                cursor: pointer;
                color: white;
                transition: 0.3s;
                border: 1px solid #D74d52;
            }
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
        margin-right: 70px;
    }

    nav {
        list-style: none;
        
        a {
            font-family: Arial, Helvetica, sans-serif;
            margin: 18px;
            text-decoration: none;
            color: #192836;
            font-weight: 800;
            text-align: center;
            font-size: small;
            transition: 0.3s;
            position: relative;

            &:hover {
                color: #D74d52;

            }

            &:hover::after{
                content: "";
                border-bottom: 2px solid #D74d52;
                display: block;
                position: absolute;
                bottom: 0;
                width: 50%;
                right: 0;
            }
        }
    }
}

</style>