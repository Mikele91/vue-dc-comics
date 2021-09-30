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
@import"src/assets/style/variables.scss";

   footer{
      background-image: url("../assets/img/footer-bg.jpg") ;
      background-size: cover;
      background-position: top;
      min-height: 20rem;
      .top-footer{
         display: flex;
         justify-content: space-between;
      }
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
   }
</style>