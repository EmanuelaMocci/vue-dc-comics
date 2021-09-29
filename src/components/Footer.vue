<template>
    <div class="footer">
        <div class="footer-top">
             <div class="contenitore-centrale">
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
        <div class="footer-bottom">

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
    height: 330px;
    width: 100%;
    background-image: url("../assets/img/footer-bg.jpg");

    .contenitore-centrale{
        max-width: 70%;
        margin: auto;
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

.footer-bottom{
    background-color: rgb(48, 48, 48);
    height: 100px;
}


</style>