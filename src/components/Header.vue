<template>
    <div class="header">
        <div class="contenitore-centrale">
            <div class="logo">
            <img src="@/assets/img/dc-logo.png" alt="logo">
        </div>
        <div class="nav">
            <ul>
                <li v-for="(item, index) in menu" :key="index">
                    <a :href="item.url" :class="item.stato == true ? 'active' : '' ">{{item.titolo}}</a>
                </li>
            </ul>
        </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Header',
    data() {
        return{
            menu: [
                {
                    titolo: 'CHARACTERS',
                    url:'#',
                    stato: false, 
                },
                {
                    titolo: 'COMICS',
                    url:'#',
                    stato: true, 
                },
                {
                    titolo: 'MOVIES',
                    url:'#',
                    stato: false, 
                },
                {
                    titolo: 'TV',
                    url:'#',
                    stato: false, 
                },
                {
                    titolo: 'GAMES',
                    url:'#',
                    stato: false, 
                },
                {
                    titolo: 'COLLECTIBLES',
                    url:'#',
                    stato: false, 
                },
                {
                    titolo: 'VIDEOS',
                    url:'#',
                    stato: false, 
                },
                {
                    titolo: 'FANS',
                    url:'#',
                    stato: false, 
                },
                {
                    titolo: 'NEWS',
                    url:'#',
                    stato: false, 
                },
                {
                    titolo: 'SHOP',
                    url:'#',
                    stato: false, 
                }
            ]
        }
    }
}
</script>

<style lang="scss" scoped>
@import "../assets/style/variables";
.contenitore-centrale{
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

            .active{
                color: #0082F9;
                border-bottom: 4px solid #0082F9;
            }
        }
        
    }
}
</style>