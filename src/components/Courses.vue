<script>
export default {   
    name: 'Courses'

}
</script>


<template>
  
  <div class="courses">

      <div class="courses-text">
          <h2>Recent Courses</h2>
          <p>Whether you're considering a foundation course or an undergratuate degree master's <br> or a PhD, academics is a place where students thrive.</p>
      </div>

      <div class="course-card-container">

        
        <div class="course-card">
            <div class="card-img">
                <img src="/public/img/bruce-mars-FWVMhUa_wbY-unsplash.jpg" alt="">
            </div>
            <div class="course-price">
                <img src="" alt="">
                <span>Free</span>
            </div>
            <div class="card-text">
                <h3>UI Animation using Sketch 3, Principle App, and Flinto</h3>
                <p>This online photography course will teach you how to take amazing images and even sell...</p>
            </div>
            <div class="course-author">
                <span>Course by : University</span>
            </div>
        </div>

        <div class="course-card">
            <div class="card-img">
                <img src="/public/img/course-1-2.jpg" alt="">
            </div>
            <div class="course-price">
                <img src="" alt="">
                <span>Free</span>
            </div>
            <div class="card-text">
                <h3>The Ultimate Drawing Course - Beginner to Advanced</h3>
                <p>This online photography course will teach you how to take amazing images and even sell...</p>
            </div>
            <div class="course-author">
                <span>Course by : University</span>
            </div>
        </div>

        <div class="course-card">
            <div class="card-img">
                <img src="/public/img/william-thomas-ny6tO4ItOEY-unsplash.jpg" alt="">
            </div>
            <div class="course-price">
                <img src="" alt="">
                <span>Free</span>
            </div>
            <div class="card-text">
                <h3>Your Complete Guide to Photography</h3>
                <p>This online photography course will teach you how to take amazing images and even sell...</p>
            </div>
            <div class="course-author">
                <span>Course by : University</span>
            </div>
        </div>
        
        
        
    </div>
    <div class="student-interview">
        <img src="../../public/img/quote.png" alt="">
        <p>"Academics was committed to my success from the moment I attended an Open House. With the support of <span class="red">advisors, professors, and staff</span> I was able to thrive in courses, gain recognition through scholarships, and finish <span class="black">with confidence in my <b class="red">@academics</b> abilities.</span> "</p>
    </div>
  </div>

</template>


<style scoped lang="scss">
    
    .courses{
        padding-top: 100px;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center ;

        .courses-text{
            line-height: 2.7;
            width: 800px;
            display: flex;
            flex-direction: column;
            flex-wrap: wrap;
            text-align: center;

            h2{
                font-size: 1.9rem;
            }
            
            p{
                line-height: 1.6;
                font-size: 1.2rem;
            }
        }
    }

    .course-card-container {
        width: 1100px;
        display: flex;
        justify-content: space-between;
        align-items: center;
        margin-top: 70px;
        .course-card {
            width: 32%;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            box-shadow: 2px 2px 20px rgba(0, 0, 0, 0.07);
            
            .card-img {
                width: 100%;
                height: 200px;
                object-fit: cover;
                overflow: hidden;
                img{
                    width: 100%;
                    // height: 100%;
                }
            }
            .course-price{
                text-align: start;
                width: 90%;
                margin-top: 20px;   
                span{ 
                    background: linear-gradient(to top, #FFE1E2 50%, transparent 50%);
                }
            }
            .card-text{
                margin: 28px;
                width: 90%;
                margin-top: 10px;
                h3{
                    line-height: 1.5;
                    margin-bottom: 15px;
                    font-size: 1.33rem;
                }
                p{
                    line-height: 1.8;
                    font-size: 1.2rem;
                }
            }
            .course-author{
                width: 90%;
                margin-bottom: 30px;

                span{
                    color: #D74d52;
                }
            }
        }
    }
    
    .student-interview{
        height: 100%;
        margin-top: 30px;
         img{
            width: 250px;
            position: absolute;
            left: 43vw;
            margin-top: 70px;
         }

         p{
            position: relative;
            width: 1100px;
            text-align: center;
            bottom: -80px;
            font-size: 1.9rem;
            font-family:Arial, Helvetica, sans-serif;
            .red{
                color: #D74d52;
                font-weight: 800;
                text-decoration: underline;
                text-underline-offset: 0.3em;
                text-decoration-thickness: 1px;
            }
            .black{
                color: black;
                font-weight: 800;
            }
         }
    }

</style>