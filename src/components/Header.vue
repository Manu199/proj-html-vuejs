<script>
export default {
    name: 'Header'
}
</script>


<template>
 
 <header>

     
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
        <img src="../../public/img/jumbotron_1.PNG" alt="">
 </header>

</template>


<style scoped lang="scss">

header {
    position: relative;
    z-index: 1;
    img{ 
        position: absolute;
        top: 0;
        width: 100%;
    }
}
.header-container {
    width: 98%;
    height: 75px;
    display: flex;
    align-items: center;
    justify-content: space-around;
    background-color: white;
    position: relative;
    z-index: 1;
    img {
        width: 25%;
        margin-top: 44px;
        margin-left: 30%;
        z-index: 99;
        position: relative;
    }

    nav {
        list-style: none;
        margin-right: 20px;
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