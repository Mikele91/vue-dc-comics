<template>
  <div class="container">
            <div class="card">
                <img :src= prod.thumb alt="" class="card-img">
                <div class="card-text">{{prod.series}}</div>
            </div>
</template>

<script>
export default {
    name:"Card",
    props:["prod"]

    }

</script>

<style lang="scss" scoped>

    .card{
        width: calc(( 100% / 6 ) - 10px);
        margin :0 5px;
        padding: 5px;
        &-text{
            text-align: center;
        }
    }


</style>