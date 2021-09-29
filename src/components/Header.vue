<template>
    <div class="header">
        <div class="logo">
            <img src="@/assets/img/dc-logo.png" alt="logo">
        </div>
        <div class="nav">
            <ul>
                <li><a href="#">CHARACTERS</a></li>
                <li><a href="#">COMICS</a></li>
                <li><a href="#">MOVIES</a></li>
                <li><a href="#">TV</a></li>
                <li><a href="#">GAMES</a></li>
                <li><a href="#">COLLECTIBLES</a></li>
                <li><a href="#">VIDEOS</a></li>
                <li><a href="#">FANS</a></li>
                <li><a href="#">NEWS</a></li>
                <li><a href="#">SHOP</a></li>
            </ul>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Header'
}
</script>

<style lang="scss" scoped>
.header{
    max-width: 70%;
    margin: auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px 0;

    ul{
        display: flex;
        
        li{
            padding-left: 30px;
            list-style: none;
            
            a{
                color: black;
                font-size: 13px;
                text-decoration: none;
                font-weight: bold;
                letter-spacing: 0.7px;
            }
        }
    }
}
</style>