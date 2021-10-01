<template>
    <div class="hero" :style="`background-image: url(${elementHero})`"></div>
</template>

<script>
export default {
    name: 'Hero',
    props: ['elementHero'],
}
</script>

<style>
    .hero{
        background-position: top;
        background-size: cover;
        background-repeat: no-repeat;
        height: 300px;
    }
</style>