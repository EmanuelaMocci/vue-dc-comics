<template>
    <div class="footer">
        <img src="@/assets/img/footer-bg.jpg" alt="sfondo footer">
        <div class="contenitore-centrale"></div>
    </div>
    
</template>

<script>
export default {
    name: 'Footer'
}
</script>

<style lang="scss" scoped>
.footer{
    img{
        width: 100%;
        height: 500px;
    }
}
.contenitore-centrale{
    max-width: 70%;
    margin: auto;
}

</style>