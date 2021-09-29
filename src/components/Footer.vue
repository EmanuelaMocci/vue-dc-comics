<template>
    <div class="footer">
        <div class="footer-top">
             <div class="contenitore-centrale"></div>
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
    height: 300px;
    width: 100%;
    background-image: url("../assets/img/footer-bg.jpg");

    .contenitore-centrale{
        max-width: 70%;
        margin: auto;
    }
}

.footer-bottom{
    background-color: rgb(48, 48, 48);
    height: 100px;
}


</style>