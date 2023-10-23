<script>
export default {
    name: 'Partner'
}
</script>


<template>
  
<div class="jumbotron">

    <h2>Since 2000, weve been partening with education leaders to <br> <span>increase equity and achievement</span> for all students.</h2>
  
    <div class="card-container container">
        <div class="card card-left">
            <img src="/svg/svg-0.svg" alt="">
            <h4>Online Coaching</h4>
            <p>Lorem ipsum is simple dummy text of the print ing and typesetting has been the industrys</p>
        </div>
        <div class="card">
            <img src="/svg/svg-1.svg" alt="">
            <h4>Consulation</h4>
            <p>Lorem ipsum is simple dummy text of the print ing and typesetting has been the industrys</p>
        </div>
        <div class="card card-right">
            <img src="/svg/svg-2.svg" alt="">
            <h4>Life Programs</h4>
            <p>Lorem ipsum is simple dummy text of the print ing and typesetting has been the industrys</p>
        </div>        
    </div>

    <div class="course-stats">
        
        <div class="statistic">

            <div class="img-stats">
                <img src="/public/img/counter-shape-1-1-1.png" alt="">
            </div>

            <div class="text-stats">
                <p class="orange-text number">6500</p>
                <span class="orange-plus orange-text"> +</span>
                <p class="p-text">Happy Clients</p>
            </div>

        </div>


        <div class="statistic">

            <div class="img-stats">
                <img src="/public/img/counter-shape-2-1-1.png" alt="">
            </div>

            <div class="text-stats">
                <p class="red-text number">200</p>
                <span class="red-plus red-text"> +</span>
                <p class="p-text">Happy Clients</p>
            </div>

        </div>


        <div class="statistic">

            <div class="img-stats">
                <img src="/public/img/counter-shape-3-1-1.png" alt="">
            </div>

            <div class="text-stats">
                <p class="green-text number">100</p>
                <span class="percentage green-text"> %</span>
                <p class="p-text">Happy Clients</p>
            </div>
           
        </div>
        
    </div>

</div>


</template>


<style scoped lang="scss">

    .jumbotron  {
        height: 100%;
        width: 100%;
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
        img{
            top: 75px;
            width: 100%;
        }
        h2{
            text-align: center;
            line-height: 1.7;
            font-size: 2.0rem;
            font-family: 'Nunito Sans', sans-serif; 
            span{
                color: #D74d52;
                font-weight: 800;
            }
        }
    }

    .card-container{

        width: 1200px;
        display: flex;
        justify-content: space-between;
        align-items: center;
        margin-top: 70px;
        .card{
            margin-top: 0px;
            width: 30%;
            height: fit-content;
            display: flex;
            flex-direction: column;
            align-items: center;
            text-align: center;
            box-shadow: 2px 2px 20px rgba(0, 0, 0, 0.07);
            color: #192836;
            img{
                width: 17%;
                padding-top: 40px;
            }
            h4{
                padding-top: 25px;
                font-size: 1.3rem;
            }
            p{
                margin: 20px 40px;
                line-height: 2;
                font-size: 1.1rem;
                margin-bottom: 80px;
            }
        }
    }

    .card-left{
        margin-left: 40px;
    }
    .card-right{
        margin-right: 40px;
    }
    .course-stats{
        display: flex;
    }


    .course-stats{
        width: 1100px;
        display: flex;
        justify-content: space-between;
    }

    .statistic {
        p.number{
            font-family: 'Nunito Sans', sans-serif;
            font-size: 2.5rem;
            font-weight: 800;
        }
        .img-stats{
            position: relative;
            width: 90px;
            right: 100%;
            top: 80%;
        }
        .text-stats{
            display: flex;
            position: absolute;
            p.number{
                right: 123%;
                position: absolute;
            }
            span{
                right: 85%;
                position: absolute;
            }
            p.p-text{
                font-size: 1.2rem;
                line-height: 2.5;
                margin-left: 30px;
            }
                
            
        }
    }
    .orange-text {
        color: #F28202;
     }
     .orange-plus {
         font-size: 3.2rem;
         font-weight: 400;
     }
    .red-text {
        color: #D74d52;
        font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
     }
     .red-plus {
         font-size: 3.2rem;
         font-weight: 400;
     }

     .green-text {
        color: #3ADC79;
     }

     .percentage {
        font-size: 2.8rem;
     }
</style>