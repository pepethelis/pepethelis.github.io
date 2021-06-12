<template>
   <div id="portfolio" class="component gray">
      <div class="container">
         <div class="row">
            <div class="col-lg-12">
               <h1 class="text header1">
                  Portfolio
               </h1>
            </div>
            <div class="col-lg-12">
               <div class="container-fluid">
                  <div class="row">
                     <div class="col-lg-3 col-sm-6">
                        <div class="card">
                        <img src="../assets/552831.jpg" class="card-img-top" alt="...">
                        <div class="card-body">
                           <h5 class="card-title">Card title</h5>
                           <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                           <a href="#" class="btn btn-outline-primary">Go to work(Git)</a>
                        </div>
                        </div>
                     </div>
                     <div class="col-lg-3 col-sm-6">
                        <div class="card">
                        <img src="../assets/552831.jpg" class="card-img-top" alt="...">
                        <div class="card-body">
                           <h5 class="card-title">Card title</h5>
                           <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                           <a href="#" class="btn btn-outline-primary">Go somewhere</a>
                        </div>
                        </div>
                     </div>
                     <div class="col-lg-3 col-sm-6">
                        <div class="card">
                        <img src="../assets/552831.jpg" class="card-img-top" alt="...">
                        <div class="card-body">
                           <h5 class="card-title">Card title</h5>
                           <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                           <a href="#" class="btn btn-outline-primary">Go somewhere</a>
                        </div>
                        </div>
                     </div>
                     <div class="col-lg-3 col-sm-6">
                        <div class="card">
                        <img src="../assets/552831.jpg" class="card-img-top" alt="...">
                        <div class="card-body">
                           <h5 class="card-title">Card title</h5>
                           <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                           <a href="#" class="btn btn-outline-primary">Go somewhere</a>
                        </div>
                        </div>
                     </div>
                     
                  </div>
               </div>
            </div>
         </div>
      </div>
   </div>
</template>

<script>
export default {
  name: 'Portfolio',
  props: {
    msg: String
  }
}
</script>
<style scoped>
.card{
   box-shadow: 2px 4px 8px 0px rgba(34, 60, 80, 0.2);
   min-width: 17vw;
}
.card:hover{
   animation-duration: 2s;
   box-shadow: 1px 14px 49px 3px rgba(34, 60, 80, 0.2);
}
.text{
   font-family: 'Montserrat';
   font-style: normal;
   font-weight: 500;
   line-height: 150%;
   letter-spacing: 0.01em;
   color: black;
}
.btn{
   box-shadow: 2px 4px 8px 0px #007bff38;
}
</style>