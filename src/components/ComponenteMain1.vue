<template>
    <div class="componente1">
        <div class="contenitore-centrale">
            <h2> --> Contents goes here </h2>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>

.componente1{
    background-color: #1C1C1C;

    .contenitore-centrale{
    max-width: 70%;
    margin: auto;
    height: 150px;
    display: flex;
    align-items: center;
 
        h2{
            color: white;
        }
    }
}


</style>