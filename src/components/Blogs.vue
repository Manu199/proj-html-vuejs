<script>
export default {
    name: 'Blogs'
}
</script>


<template>
  
    <div class="blogs">

        <div class="blogs-container">

            <h2>Latest From Our Blogs</h2>
            <p>Whether you're considering a foundation course or an undergratuate degree master's <br> or a PhD, academics is a place where students thrive.</p>

            <div class="blogs-card-container">

                <div class="blogs-card">
                    
                    <div class="card-img">
                        <img src="/public/img/news-3-2.jpg" alt="">
                    </div>
                    <div class="blog-info">
                        
                        <i class="fa-regular fa-user"></i>
                        <span>Admin</span>

                        <i class="fa-regular fa-folder-closed"></i>
                        <span>University</span>
                        
                    </div>
                    <div class="card-text">
                        <h3>Peer pressire changes how teens rackle inequity</h3>

                        <span>------------</span>
                    </div>
                    <div class="link-more">
                        <span>Read more <i class="fa-solid fa-angle-right"></i></span>
                    </div>

                </div>

                <div class="blogs-card">
                    
                    <div class="card-img">
                        <img src="/public/img/news-2-2.jpg" alt="">
                    </div>
                    <div class="blog-info">
                        
                        <i class="fa-regular fa-user"></i>
                        <span>Admin</span>

                        <i class="fa-regular fa-folder-closed"></i>
                        <span>University</span>
                        
                    </div>
                    <div class="card-text">
                        <h3>Peer pressire changes how teens rackle inequity</h3>

                        <span>------------</span>
                    </div>
                    <div class="link-more">
                        <span>Read more <i class="fa-solid fa-angle-right"></i></span>
                    </div>

                </div>

                <div class="blogs-card">
                    
                    <div class="card-img">
                        <img src="/public/img/news-1-2.jpg" alt="">
                    </div>
                    <div class="blog-info">
                        
                        <i class="fa-regular fa-user"></i>
                        <span>Admin</span>

                        <i class="fa-regular fa-folder-closed"></i>
                        <span>University</span>
                        
                    </div>
                    <div class="card-text">
                        <h3>Peer pressire changes how teens rackle inequity</h3>

                        <span>------------</span>
                    </div>
                    <div class="link-more">
                        <span>Read more <i class="fa-solid fa-angle-right"></i></span>
                    </div>

                </div>

            </div>

        </div>

    </div>

</template>


<style scoped lang="scss">

.blogs {
    width: 100%;
    margin-top: 500px;
    display: flex;
    justify-content: center;
    align-items: center;
    .blogs-container {
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
        width: 1200px;

        h2 {
            font-size: 2rem;
        }

        p {
            margin-top: 30px;
            font-size: 1.3rem;
            line-height: 1.8;
            text-align: center;
        }

        .blogs-card-container {
            margin-top: 70px;
            width: 1140px;
            display: flex;
            justify-content: space-between;
            .blogs-card {
                width: 31.5%;
                box-shadow: 2px 2px 20px rgba(0, 0, 0, 0.07);   


                img{
                    width: 100%;
                }

                .blog-info {
                    
                    margin-top: 30px;
                    i {
                        margin-left: 30px;
                    }

                    span{
                        margin-left: 8px;
                    }
                }

                .card-text {
                    width: 80%;
                    margin-left: 30px;
                    margin-top: 20px;

                    h3 {
                        font-size: 1.3rem;
                        line-height: 1.5;
                        margin-bottom: 10px;
                    }

                    span {
                        font-size: 1.3rem;
                        color: #D74d52;
                        letter-spacing: -2px;
                    }
                }

                .link-more {
                    margin-top: 35px;
                    padding-bottom: 30px;
                    span {
                        margin-left: 30px;
                    }
                }
            }
        }
    }
}

</style>