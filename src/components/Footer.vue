<script>
export default {
    name: 'Footer'
}
</script>

<template>
  
  <footer>
    <div class="email-box">

        <div class="email-card">

            <div class="input-box">
                <input type="text" placeholder="Subscribe to our newsletter">
                <button>Register</button>
            </div>
            <div class="email-info">
                <p><span>Insights is Pickwik</span> University's thjought leadership publication for sharing knowledge on management, technology and innovation.</p>
                <span>Take me there <i class="fa-solid fa-angle-right"></i></span>
            </div>

        </div>

    </div>

    <div class="lists">


        <div class="lists-container">
            
            <div class="contact-list list-box">
                <h4>Contact Us</h4>
                <ul>
                    <li><i class="fa-solid fa-location-dot" style="color: #a3b5ca;"> </i>  900 Wood Street, MI New York 48607</li>
                    <li><i class="fa-solid fa-square-phone" style="color: #a3b5ca;"> </i>  +56 345 678 000-09</li>
                    <li><i class="fa-solid fa-envelope" style="color: #a3b5ca;"></i>  info@example.com</li>
                </ul>
            </div>
    
            <div class="support-list list-box">
                <h4>Support Us</h4>
                <ul>
                    <li><i class="fa-solid fa-chevron-right" style="color: #a3b5ca;"></i> Privacy</li>
                    <li><i class="fa-solid fa-chevron-right" style="color: #a3b5ca;"></i> Terms</li>
                    <li><i class="fa-solid fa-chevron-right" style="color: #a3b5ca;"></i> Cookie Policy</li>
                    <li><i class="fa-solid fa-chevron-right" style="color: #a3b5ca;"></i> Sitemap</li>
                </ul>
            </div>
    
            <div class="explore-list list-box">
                <h4>Explore</h4>
                <ul>
                    <li><i class="fa-solid fa-chevron-right" style="color: #a3b5ca;"></i> Accomodation</li>
                    <li><i class="fa-solid fa-chevron-right" style="color: #a3b5ca;"></i> Arts Academics</li>
                    <li><i class="fa-solid fa-chevron-right" style="color: #a3b5ca;"></i> Central Services</li>
                    <li><i class="fa-solid fa-chevron-right" style="color: #a3b5ca;"></i> Conferences and Events</li>
                    <li><i class="fa-solid fa-chevron-right" style="color: #a3b5ca;"></i> Food and Drink</li>
    
    
                </ul>
            </div>
    
            <div class="visit-list list-box">
                <h4>Visit</h4>
                <ul>
                    <li><i class="fa-solid fa-chevron-right" style="color: #a3b5ca;"></i> Admission</li>
                    <li><i class="fa-solid fa-chevron-right" style="color: #a3b5ca;"></i> Contact Us</li>
                    <li><i class="fa-solid fa-chevron-right" style="color: #a3b5ca;"></i> FAQs</li>
                    <li><i class="fa-solid fa-chevron-right" style="color: #a3b5ca;"></i> Request Information</li>
                    <li><i class="fa-solid fa-chevron-right" style="color: #a3b5ca;"></i> Privacy Notice</li>
                </ul>
            </div>

        </div>

    </div>


    <div class="footer-bottom">
        <div class="square">
            <img src="/public/svg/svg-3.svg" alt="">

        </div>
        <div class="extra-info">
            <div class="copyright">
                <span><i class="fa-regular fa-copyright"></i>Copyright 2020 tophive. All Rights Reserved.</span>
            </div>
            <ul>
                <li>Privacy</li>
                <li>Terms</li>
                <li>Cookie Policy</li>
                <li>Sitemap</li>
            </ul>
        </div>
    </div>

  </footer>

</template>


<style scoped lang="scss">

    footer{
        margin-top: 1PX;
        width: 100%;
        height: 670px;
        background-color: #192735;

        .email-box {
            width: 100%;
            display: flex;
            justify-content: center;
            align-items: center;

            .email-card {
                width: 1110px;
                display: flex;
                height: 170px;
                align-items: center;
                box-shadow: 0 0 25px  rgba(0, 0, 0, 0.09);
                margin-top: 80px;
                .input-box {
                    display: flex;

                    input {
                        padding: 20px;
                        border: 0;
                        width: 285px;
                        height: 60px;
                        margin-left: 45px;
                        cursor: pointer;
                    }
                    button {
                        background-color: #D74D52;
                        color: white;
                        border: 0;
                        padding: 20px 30px;
                        cursor: pointer;
                    }
                }
                .email-info {
                    margin-left: 70px;
                    color: #A3B5CA;
                    line-height: 2;
                    font-size: 0.9rem;
                    margin-top: 5px;
                    p {
                        line-height: 1.4;
                        span{
                            color: #D74D52;
                            text-decoration: underline;
                            text-underline-offset: 4px;
                            text-decoration-color: white;
                            font-weight: 600;
                        }
                    }
                    span{
                        font-weight: 600;
                        margin-top: 40px;
                        cursor: pointer;
                        color: white;
                    }
                }
            }
        }
        .lists {
            display: flex;
            justify-content: center;
            align-items: center;
        }
        .lists-container {
            display: flex;
            justify-content: center;
            margin-top: 80px;
            width: 1110px;

            .list-box {
                width: 25%;
                h4{
                    color: white;
                    font-size: 1.3rem;
                    margin-bottom: 30px;
                    cursor: pointer;
                }
                ul{
                    list-style: none;
                    li{
                        margin-top: 20px;
                        font-size: 0.8rem;
                        color: #A3B5CA;
                        font-weight: bold;
                        cursor: pointer;
                        
                       
                        i{
                            margin-right: 4px;
                        }
                    }
                    li:hover{
                            margin-left: 10px;
                            color: #D74D52;
                            
                            i{
                                color: #D74D52 !important;
                            }
                        }
                }
            }
            .contact-list {
                li {
                    font-size: 0.7rem;
                    width: 60%;
                    line-height: 1.5;
                    i{
                        font-size: small;
                        font-weight: 600;
                    }
                }
            }
        }

        .footer-bottom {

            .square{
                width: 100%;
                height: 50px;

                img {
                    width: 40px;
                    height: 40px;
                    background-color: #EBEBEB;
                    float: right;
                    margin-top: 7px;
                    margin-right: 40px;
                }
            }
        }
        .extra-info {
            background-color: #15222E;
            display: flex;
            margin-top: 28px;
            height: 50px;
            align-items: center;
            justify-content: space-around;
            color: #A3B5CA;
            font-size: 0.8rem;
            padding-left: 40px;
            padding-right: 40px;

            ul {
                display: flex;
                list-style: none;
                
                li{
                    margin-left: 20px;
                    cursor: pointer;

                    &:hover {
                        text-decoration: underline;
                    }
                }
            }
        }
    }
</style>