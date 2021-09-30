<template>
<div class="cards-container">
    <img :src="element.thumb" :alt="element.series">
    <div class="titolo">
        {{element.series}}
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

.cards-container{
    width: calc(100% / 6 - 20px);
    margin: 0 10px;

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
</style>