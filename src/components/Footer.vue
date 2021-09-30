<template>
   <footer>
      <div class="container">
         <div class="top-footer">
            <div class="list">
               <div class="col-list">
               <div class="section-list">

               <h3>Titolo List</h3>
            <ul>
               <li><a href="">link 1</a></li>
               <li><a href="">link 1</a></li>
               <li><a href="">link 1</a></li>
               <li><a href="">link 1</a></li>
               <li><a href="">link 1</a></li>

            </ul>
               </div>
                 <div class="section-list">

               <h3>Titolo List</h3>
            <ul>
               <li><a href="">link 1</a></li>
               <li><a href="">link 1</a></li>
               <li><a href="">link 1</a></li>
               <li><a href="">link 1</a></li>
               <li><a href="">link 1</a></li>

            </ul>
               </div>

               </div>
                 <div class="col-list">
               <div class="section-list">

               <h3>Titolo List</h3>
            <ul>
               <li><a href="">link 1</a></li>
               <li><a href="">link 1</a></li>
               <li><a href="">link 1</a></li>
               <li><a href="">link 1</a></li>
               <li><a href="">link 1</a></li>

            </ul>
               </div>
                 <div class="section-list">

               <h3>Titolo List</h3>
            <ul>
               <li><a href="">link 1</a></li>
               <li><a href="">link 1</a></li>
               <li><a href="">link 1</a></li>
               <li><a href="">link 1</a></li>
               <li><a href="">link 1</a></li>

            </ul>
               </div>

               </div>

            </div>
            <div class="img-dc">
            <!-- <img src="@/assets/img/dc-logo-bg.png" alt=""> -->
            </div>
         </div>
         <div class="bottom-footer">

         </div>

      </div>

   </footer>
</template>

<script>
export default {
    name:"Footer",

}
</script>

<style lang="scss" scoped>
@import"../assets/style/variables.scss";

   footer{
      background-image: url("../assets/img/footer-bg.jpg") ;
      background-size: cover;
      background-position: top;
      .top-footer{
         min-height: 25rem;
         display: flex;
         justify-content: space-between;
         .list{
               display: flex;
               color: white;
            .col-list{
               margin: 0 1.25rem
            }  
         
         li{
            @include list;
   
            a{
               color: white;
               @include list;
            }
         }
      }
         .img-dc{
         background-image: url("../assets/img/dc-logo-bg.png");
         width: 50%;
         background-size: cover;
         background-position:center ;
      }
      }
      
   }
</style>