<template>
    <div class="footer">
        <div class="footer-top">
             <div class="contenitore-centrale">
                 <div class="footer-sinistra">
                    <div class="lista">
                        <h4>DC COMICS</h4>
                        <ul>
                            <li><a href="#">Characters</a></li>
                            <li><a href="#">Comics</a></li>
                            <li><a href="#">Movies</a></li>
                            <li><a href="#">TV</a></li>
                            <li><a href="#">Games</a></li>
                            <li><a href="#">Videos</a></li>
                            <li><a href="#">News</a></li>
                        </ul>

                        <h4>SHOP</h4>
                        <ul>
                            <li><a href="#">Shop DC</a></li>
                            <li><a href="#">Shop DC Collectibles</a></li>
                        </ul>
                    </div>
                
                    <div class="lista">
                        <h4>DC</h4>
                        <ul>
                            <li><a href="#">Terms Of Use</a></li>
                            <li><a href="#">Privacy policy (New)</a></li>
                            <li><a href="#">Ad Choices</a></li>
                            <li><a href="#">Advertising</a></li>
                            <li><a href="#">Jobs</a></li>
                            <li><a href="#">Subscriptions</a></li>
                            <li><a href="#">Talent Workshops</a></li>
                            <li><a href="#">CPSC Certificates</a></li>
                            <li><a href="#">Ratings</a></li>
                            <li><a href="#">Shop Help</a></li>
                            <li><a href="#">Contact Us</a></li>
                        </ul>
                    </div>

                    <div class="lista">
                        <h4>SITES</h4>
                        <ul>
                            <li><a href="#">DC</a></li>
                            <li><a href="#">MAD Magazine</a></li>
                            <li><a href="#">DC Kids</a></li>
                            <li><a href="#">DC Universe</a></li>
                            <li><a href="#">DC Power Visa</a></li>
                        </ul>
                    </div>
                </div>  
            </div>
        </div>
        <div class="footer-bottom">
            <div class="contenitore-centrale">
                <div class="sign-up">
                    <button><a href="#">SIGN-UP NOW!</a></button>
                </div>

                <div class="follow-icone">
                    <h3>FOLLOW US</h3>
                    <img src="../assets/img/footer-facebook.png" alt="">
                    <img src="../assets/img/footer-twitter.png" alt="">
                    <img src="../assets/img/footer-youtube.png" alt="">
                    <img src="../assets/img/footer-pinterest.png" alt="">
                    <img src="../assets/img/footer-periscope.png" alt="">
                </div>
            </div>
        </div>
       
    </div>
    
</template>

<script>
export default {
    name: 'Footer'
}
</script>

<style lang="scss" scoped>
.footer-top{
    height: 320px;
    width: 100%;
    background-image: url("../assets/img/dc-logo-bg.png"), url("../assets/img/footer-bg.jpg");
    background-position: right 25% center, left top;
    background-size: 485px, cover;
    background-repeat: no-repeat, no-repeat;


    .contenitore-centrale{
        max-width: 70%;
        margin: auto;
        display: flex;

        .footer-sinistra{
            display: flex;

            .lista{
            padding-right: 30px;

            h4{
                color: white;
            }
            ul{
                padding: 0;

                li{
                    list-style: none;

                    a{
                        color: grey;
                        text-decoration: none;
                        font-size: 12px;
                        letter-spacing: 0.7px;
                    }
                }
                }
            }
        }
    }
}
.footer-bottom{
        background-color: rgb(48, 48, 48);
        height: 100px;

        .contenitore-centrale{
            max-width: 70%;
            height: 100%;
            margin: auto;
            display: flex;
            justify-content: space-between;
            align-items: center;

            .sign-up{

                button{
                    background-color: rgb(48, 48, 48);
                    border: none;
                    border: 2px solid #0082F9;
                    padding: 10px;
                }
                a{
                    color: white;
                    text-decoration: none;
                }
            }
            .follow-icone{
                display: flex;
                align-items: center;

                h3{
                    color: #0082F9;
                    margin-right: 10px;
                }

                img{
                    width: 30px;
                    height: 30px;
                    margin-left: 10px;
                }
            }
    }      
}




</style>