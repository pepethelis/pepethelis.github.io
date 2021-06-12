<template>
   <div id="about" class="component">
      <div class="container">
         <div class="row">
            <div class="col-lg-12">
               <h1 class="text header header1">
                  About me
               </h1>
            </div>
            <div class="col-lg-3 flex">
               <img src="../assets/photo_2020-05-04_15-25-04.jpg" class="pic">
            </div>
            <div class="col-lg-5">
               <span class="text">
                  <div class="h4">
                     Борзыкин Вадим
                  </div> 
                  <div>
                    Возраст: 19 лет 
                    
                  </div>
                  <div>
                     Специализация: Front-End
                  </div>
                  <div>
                     ВУЗ: ВНУ имени Даля
                  </div>
                  <div>
                     Курс: второй
                  </div>
                  <div>
                     Специальность: Информационные системы и технологии
                  </div>
                  
               </span>
            </div>
            <div class="col-lg-4 flex d-none d-lg-block">
               <img src="../assets/807609.jpg" id="pic2" alt="">
            </div>
         </div>
      </div>
   </div>
</template>

<script>
export default {
   name: 'About',
   props: {
      msg: String
   }
}
</script>
<style scoped>
.text{
   font-family: 'Montserrat';
   font-style: normal;
   font-weight: 500;
   line-height: 150%;
   letter-spacing: 0.01em;
   color: black;
}
.pic{
   height: 180px;
   width: auto;
   border-radius: 50%;
}
.flex{
   display: flex;
   justify-content: space-around;
}
#pic2{
   height: 180px;
   width: auto;
   border-radius: 15px;
}
</style>