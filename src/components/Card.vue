<template>

<div class="contenitore-centrale">
    <div class="cards-container">
        <img :src="element.thumb" :alt="element.series">
            <div class="titolo">
                {{element.series}}
            </div>
    </div>
</div>
    
     
</template>

<script>
export default {
    name: 'Card',
    props: ['element']
    
}
</script>

<style lang="scss" scoped>

.contenitore-centrale{
    max-width: 70%;
    margin: auto;
    display: flex;

        .cards-container{
        width: calc(100% / 6 - 20px);
        margin: 50px 10px 0 10px;

        img{
            object-fit: cover;
            object-position: top;
            width: 170px;
            height: 170px;
        }
        .titolo{
            width: 170px;
            color: white;
        }
    }
}

</style>