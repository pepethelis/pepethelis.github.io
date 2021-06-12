<template>
   <div id="header"  class="component">
      <div class="container" id="pic">
         <div class="row">
            <div class="col-md-1"></div>
            <div class="col-md-4">
               <div class="container-fluid">
                  <div class="row">
                     <div class="col-md-12">
                        <span class="nam big">
                           <div>Hello</div> 
                           Nice to meet you
                        </span> 
                     </div>
                     <div class="col-md-12" id="butt">
                        
                           <a href="#portfolio" type="button" class="btn btn-danger" id="button-shadow">
                              To Works 
                              <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-arrow-right-circle" viewBox="0 0 16 16">
                                 <path fill-rule="evenodd" d="M1 8a7 7 0 1 0 14 0A7 7 0 0 0 1 8zm15 0A8 8 0 1 1 0 8a8 8 0 0 1 16 0zM4.5 7.5a.5.5 0 0 0 0 1h5.793l-2.147 2.146a.5.5 0 0 0 .708.708l3-3a.5.5 0 0 0 0-.708l-3-3a.5.5 0 1 0-.708.708L10.293 7.5H4.5z"/>
                              </svg>
                           </a>
                        
                     </div>
                  </div>
               </div>
            </div>
            <div class="col-md-1"></div>
            <div class="col-md-6 d-none d-md-block">
               <img src="../assets/807599.jpg" id="min" class="" alt="">
            </div>
         </div>
      </div>
   </div>
</template>

<script>
export default {
  name: 'Header',
  props: {
    msg: String
  }
}
</script>
<style scoped>

a {
  color: white;
}
nav{
   background-color: rgba(255, 255, 255, 0.1);
}
#header{
   background-image: url("../assets/807609.jpg");
   height: 85vh;
   background-position: center;
   background-repeat: no-repeat; /* Do not repeat the image */
   margin: 0;
	background-size: cover;
}

#button-shadow{
   
   padding: 15px 25px;
   box-shadow: 0 2 10px  lightcoral;
}
#button-shadow:hover{
   padding: 15px 25px;
   box-shadow: 0 0 15px 2px rgba(240, 128, 128, 0.9);
}
#nav{
   background-color: rgba(100, 100, 100, 0.1);
   padding: 15px;
}
.nam{
   color: white;
   font-family: 'Salsa', cursive;
   
}
#pic{
   height: 50vh;
   padding-top: 150px;
}
#butt{
   margin-top: 10px;
}
#min{
   height: auto;
   min-width: 300px;
   width: 35vw;
   border-radius: 15px;
}
.big{
   font-family: Poppins;
   font-style: normal;
   font-weight: 500;
   font-size: 64px;
   line-height: 110%;

   /* or 96px */
   letter-spacing: 0.01em;

   /* Mono/black */
   color: white;
}
</style>