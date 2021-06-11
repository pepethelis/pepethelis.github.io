<template>
  <div id="app">
    <Navbar />
    <Header />
    <About />
    <Portfolio />
    <Contact />
    <Social />
    <Footer />
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Footer from './components/Footer.vue'
import About from './components/About.vue'
import Portfolio from './components/Portfolio.vue'
import Navbar from './components/Navbar.vue'
import Contact from './components/Contact.vue'
import Social from './components/Social.vue'
export default {
  name: 'App',
  components: {
    Header,
    Footer,
    About,
    Portfolio,
    Navbar,
    Contact,
    Social
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin: 0;
}
.component{
  padding: 20px 0 50px;
}
.header1{
  text-align: center;
  margin: 0 0 20px;
  margin: 20px
}
.gray{
  background-color: rgb(248, 248, 248)  
}
@import url('https://fonts.googleapis.com/css2?family=Pacifico&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Salsa&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Montserrat&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Poppins&display=swap');
</style>
