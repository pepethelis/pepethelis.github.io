<template>
   <div id="navbar">
      <nav class="navbar">
         <div class="container-fluid">
            <span class="navbar-brand nam">
               pepethelis
            </span>
            <div class="d-flex">
               <div class="container-fluid">
                  <div class="row">
                     <div class="col">
                        <a href="#header">
                           <span>HOME</span>
                        </a>
                     </div>
                     <div class="col">
                        <a href="#about">
                           <span>ABOUT</span>
                        </a>
                     </div>
                     <div class="col">
                        <a href="#portfolio">
                           <span>PORTFOLIO</span>
                        </a>
                     </div>
                     <div class="col">
                        <a href="#contact">
                           <span>CONTACT</span>
                        </a>
                     </div>
                     <div class="col">
                        <a href="#social">
                           <span>SOCIAL</span>
                        </a>
                     </div>
                  </div>
               </div>
            </div>
         </div>
      </nav>
   </div>
</template>

<script>
export default {
  name: 'Navbar',
  props: {
    msg: String
  }
}
</script>
<style scoped>
#navbar{
  position: fixed;
  z-index: 5;
  width: 100%;
  color: black;
  background-color: rgba(236, 236, 236, 0.5);
}
.nam{
  color: black;
  font-family: 'Pacifico', cursive;
}
a {
  color: black;
}
</style>