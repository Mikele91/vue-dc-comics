<template>
            <div class="card">
                <img :src= prod.thumb alt="" class="card-img">
                <div class="card-text">{{prod.series}}</div>
            </div>
</template>

<script>
export default {
    name:"Card",
    props:['prod']

    }

</script>

<style lang="scss" scoped>

.card{
        width: calc(( 100% / 6 ) - .625rem);
        margin :0 .3125rem;
        padding: .3125rem;
        &-text{
            text-align: center;
        }
    }




</style>