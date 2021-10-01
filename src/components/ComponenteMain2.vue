<template>
    <div class="componente2">
        <div class="contenitore-centrale">
            <div class="img">
                <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                <span>DIGITAL COMINCS</span>
            </div>

            <div class="img">
                <img src="../assets/img/buy-comics-merchandise.png" alt="">
                <span>DC MERCHANDISE</span>
            </div>

            <div class="img">
                <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                <span>SUBSCRIPTION</span>
            </div>
            
            <div class="img">
                <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                <span>COMIC SHOP LOCATOR</span>
            </div>

            <div class="img">
                <img class="visa" src="../assets/img/buy-dc-power-visa.svg" alt="">
                <span>DC POWER VISA</span>
            </div>
            
        </div>
     
    </div>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>

    .componente2{
        background-color: #0082F9;
        height: 150px;
        display: flex;

        .contenitore-centrale{
            display: flex;
            margin: auto;

            .img{
                display: flex;
                align-items: center;

                img{
                    height: 45px;
                    padding: 0 20px;
                }
                span{
                    color: white;
                    font-size: 15px;
                    padding-right: 25px;
                }
                &:last-child img{
                    width: 50px;
                }
            }    
        }
    }

</style>