<template>
    <header>
        <div class="container">
            <div class="logo">
                <img src="@/assets/img/dc-logo.png" alt="">
            </div>
            <nav>
                <ul>
                    <li v-for="(link, index) in menu" :key="index"><a :class="{active : link.current}" href="link.url">{{link.text}}</a></li>
                </ul>
            </nav>
        </div>

    </header>
</template>

<script>
export default {
    name:"Header",
    data(){
        return{
            menu:[
                {
                    text:"Charaters",
                    url:"#",
                    current: false,
                },   
                {
                    text:"Movies",
                    url:"#",
                    current: false,
                },
                {
                    text:"Tv",
                    url:"#",
                    current: true,
                },
                {
                    text:"Comics",
                    url:"#",
                    current: false,
                },
                {
                    text:"Games",
                    url:"#",
                    current: false,
                },
                {
                    text:"Collectibles",
                    url:"#",
                    current: false,
                }, 
                {
                    text:"Videos",
                    url:"#",
                    current: false,
                },
                {
                    text:"Fans",
                    url:"#",
                    current: false,
                },
                {
                    text:"News",
                    url:"#",
                    current: false,
                },
                {
                    text:"Shop",
                    url:"#",
                    current: false,
                },
            ],
        }
    }


}
</script>

<style lang="scss" scoped>
@import"src/assets/style/variables.scss";
header{
    margin: 1.25rem 0;
}
    .container{
        justify-content:space-between ;
        align-items: center;
        display: flex;
   
    nav ul {
        display: flex;
    li {
        
        @include list;
        a{
            @include list;
            color:$colorDc;
            padding:1rem;
            

            &.active{
             color: red ;
             border-bottom: 2px solid $colorDc;
            }
        }
    }
    }
 }

    
</style>