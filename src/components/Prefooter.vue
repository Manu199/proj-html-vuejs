<script>
export default {
    name: 'Prefooter'
}
</script>


<template>
  
    <div class="prefooter">

        <div class="img">
            <img src="/public/img/gallery-3-3.jpg" alt="">
            <div class="color">
                <span><i class="fa-solid fa-eye"></i></span>
                <p>Driving Innovation</p>
            </div>
        </div>

        <div class="img">
            <img src="/public/img/news-3-2.jpg" alt="">
            <div class="color">
                <span><i class="fa-solid fa-eye"></i></span>
                <p>Driving Innovation</p>
            </div>
        </div>

        <div class="img">
            <img src="/public/img/gallery-1-3.jpg" alt="">
            <div class="color">
                <span><i class="fa-solid fa-eye"></i></span>
                <p>Driving Innovation</p>
            </div>
        </div>

        <div class="img">
            <img src="/public/img/gallery-2-3.jpg" alt="">
            <div class="color">
                <span><i class="fa-solid fa-eye"></i></span>
                <p>Driving Innovation</p>
            </div>
        </div>


    </div>

</template>


<style scoped lang="scss">

 .prefooter{
    width: 100vw;
    height: 325px;
    display: flex;
    margin-top: 120px;
    .img {
        width: 25vw;
        height: 325px;
        position: relative;
        
        img{
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        .color {
            z-index: 2;
            background-color: #d74d52cf;
            position: absolute;
            width: 100%;
            height: 100%;
            top: 0px;
            justify-content: center;
            flex-direction: column;
            align-items: center;
            display: none;
            
            span{
                color: #ffffff;
                font-size: 1.3rem;
                padding: 25px;
                border-radius: 50%;
                background-color: rgba($color: #ffffff, $alpha: 0.4)
            }
            p {
                color: white;
                margin-top: 10px;
                font-size: 1.2rem;
            }
        }
        &:hover .color{
            display: flex;
        }

    }
 }

</style>