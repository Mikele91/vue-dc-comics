<template>
   <footer>
      <div class="container">
         <div class="top-footer">
         <h2>Sono il Footer</h2>
         <img src="@/assets/img/dc-logo-bg.png" alt="">
         </div>
         <div class="bottom-footer">

         </div>

      </div>

   </footer>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
   footer{
      background-image: url("../assets/img/footer-bg.jpg") ;
      background-size: cover;
      background-position: top;
      min-height: 20rem;
      .top-footer{
         display: flex;
         justify-content: space-between;
      }
   }
</style>