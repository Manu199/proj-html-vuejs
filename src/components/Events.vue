<script>
export default {
    name: 'Events'
}

</script>


<template>
  
  <div class="event">

      <div class="event-container">
  
          <div class="img-behind">
              <img src="../../public/img/video-bg-3.jpg" alt="">
              <!-- <i class="fa-solid fa-play"></i> -->
          </div>
  
          <div class="img-front">
              <img src="../../public/svg/svg-3.svg" alt="">
                <div class="text">
                    <div class="title">
                        <h3>Upcoming Events</h3>
                    </div>
                    <p>Princeton offers admission information sessions and student-led tours to campus visitors</p>
                    <span>Learn more <i class="fa-solid fa-angle-right"></i></span>
                    <p>Admission iformation sessions and student-òed tours to campus visitors</p>
                    <span>Learn more <i class="fa-solid fa-angle-right"></i></span>
                    <div class="locations">
                        <span><i class="fa-regular fa-map"> </i>  Event Locations <i class="fa-solid fa-angle-right"></i></span>
                    </div>
                </div>
          </div>
  
      </div>

  </div>

</template>


<style scoped lang="scss">

.event{
    display: flex;
    justify-content: center;
    align-items: center;
    position: relative;

}
    .event-container{
        margin-top: 450px;
        width: 1000px;
        display: flex;
        justify-content: space-between;
        align-items: center;
        

        .img-behind {
            position: absolute;
        }
        .img-front img{
            background-color: white;
            width: 650px;
            height: 580px;
            position: absolute;
            left: 45.5%;
            top: 260px;
            box-shadow: 2px 2px 20px rgba(0, 0, 0, 0.07);

        }
        .text{
            z-index: 1;
            position: absolute;
            width: 650px;
            left: 45.5%;
            top: 260px;
            text-align: start;
            .title{
                text-align: center;
            }
            h3{
                margin-left: 160px;
                margin-right: 160px;
                background-color: #D74d52;
                padding: 35px 50px;
                font-size: 1.8rem;
                color: white;
                font-weight: 100;
            }
            
          p{
            font-size: 1.3rem;
            text-align: start;
            margin-left: 30px;
            width: 80%;
            font-weight: 600;
            line-height: 1.8;
            margin-top: 20px;
            margin-bottom: 20px;
          }
          
          span{
            font-size: 1rem;
            text-align: start;
            margin: 30px;
            width: 80%;
            font-weight: 600;
            line-height: 1.8;
          }

        }

        .text p:first-of-type {
            margin-top: 60px;
        }
        .locations{
            width: 100%;
            text-align: center;
            margin-top: 30px;
            
            span{
                font-weight: 800;
            }
            i{
                margin-right: 5px;
            }
        }
    }

</style>