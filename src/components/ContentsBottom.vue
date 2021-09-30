<template>
    <section>
        <div class="container">

        <nav>
            <ul>
                <li v-for="(link, index) in list" :key="index">
                    <a href="">
                        <img :src="require(`@/assets/img/${link.url}`)" :alt="link.text">
                        <div class="text">{{link.text}}</div>
                    </a>
                </li>
            </ul>
        </nav>
        </div>

    </section>
</template>

<script>
export default {
    name:"ContentsBottom",
    data(){
        return{
            list:[
                {
                    text:"Digital Comics",
                    url:'buy-comics-digital-comics.png',
                    current: false,
                },   
                {
                    text:"DC Merchandise",
                    url:'buy-comics-merchandise.png',
                    current: false,
                },  
                {
                    text:"Subscription",
                    url:'buy-comics-subscriptions.png',
                    current: false,
                },
                {
                    text:"Comics Shop Locator",
                    url:'buy-comics-shop-locator.png',
                    current: false,
                },    
                {
                    text:"Digital Comics",
                    url:'buy-dc-power-visa.svg',
                    current: false,
                },
        
            ],
        }
    }
}
</script>

<style lang="scss" scoped>
@import "../assets/style/variables.scss";
section{
    background-color:$colorDc ;
}
    .container{
        align-items: center;
        display: flex;
    nav{
        width: 100%;
    }
    nav ul {
        width: 100%;
        display: flex;
        justify-content: space-between;


        li {
        display: flex;
        @include list;
        a{
            @include list;
            color:$colorDc;
            padding:1rem;
            display: flex;
            align-items: center;
            img{
                width: 3.125rem;
                max-height: 4.375rem;

            }
            .text{
                padding: 0 .625rem;
                color: white;
            }
        }
    }
    }
}

</style>