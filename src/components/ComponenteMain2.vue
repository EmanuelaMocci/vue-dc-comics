<template>
    <div class="componente2">
        <div class="contenitore-centrale">
            <div v-for="(item, index) in menu" :key="index">
                <img src="" alt="">
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
        align-items: center;
        justify-content: space-between;

        

        .contenitore-centrale{
            display: flex;
            max-width: 70%;
            margin: auto;

            
            .img{
                display: flex;
                align-items: center;

                img{
                    height: 50px;
                }
                span{
                    color: white;
                    padding-left: 10px;
                }
            }
            
            
        }
    }

</style>