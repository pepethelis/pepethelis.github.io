<template>
   <div id="contact" class="component">
      <div class="container">
         <div class="row">
            <div class="col-lg-12">
               <h1 class="text h1 header1">
                  Contact
               </h1>
            </div>
            <div class="col-lg-6">
               <div class="row">
                  <div class="col-md-12">
                     <input type="text" placeholder="Name" class="form-control" aria-describedby="emailHelp">
                  </div>
                  <div class="col-md-12">
                     <input type="email" placeholder="Email" class="form-control" aria-describedby="emailHelp">
                  </div>
                  <div class="col-md-12">
                     <input type="text" placeholder="Theme" class="form-control" aria-describedby="emailHelp">
                  </div>
               </div>
            </div>
            <div class="col-lg-6">
               <div class="form-floating">
                  <textarea class="form-control" style="height: 155px;" placeholder="Leave a comment here" id="floatingTextarea"></textarea>
               </div>
            </div>
            <div class="col-lg-12 flex">
               <button type="submit" class="btn btn-lg">Send mail</button>
            </div>
         </div>
      </div>
   </div>
</template>

<script>
export default {
  name: 'Contact',
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
.form-control{
   margin: 10px 0;
}
.btn{
   box-shadow: 2px 4px 8px 0px rgba(34, 60, 80, 0.2);
   margin-top: 20px;
}
.btn:hover{
   box-shadow: 1px 14px 49px 3px rgba(34, 60, 80, 0.2);
}
.flex{
   display: flex;
   justify-content: space-around;
}
</style>