<template>
  <div id="app">

    <!-- usando los componentes customs -->
    <login></login>
    <temp-header></temp-header>
    <banner></banner>
    <!-- <prestamo></prestamo> -->
    <function></function>
    <Facebook></Facebook>
    <Us></Us>
    <Cases></Cases>
    <allies></allies>
    <Footer></Footer>
    <Author></Author>



  </div>
</template>


<script>

// importaccion de los components hijos
import Login from './components/Login'
import TempHeader from './components/Header'
import Banner from './components/Banner'
import Prestamo from './components/Prestamo'
import Function from './components/function'
import Facebook from './components/Facebook'
import Us from './components/Us'
import Cases from './components/Cases'
import Allies from './components/Allies'
import Footer from './components/footer'
import Author from './components/Author'


import axios from 'axios'


// exportando el component app para renderizarlo en el archivo main.js
export default {


  name: 'app',
  components: {TempHeader, Banner, Prestamo,Login,Function,Facebook,Us,Cases,Allies,Footer,Author},
  mounted(){
    this.getData()
  },
  data () {
    return {
      msg: 'Welcome to Your Vue.js App',


    }
  },
  methods:{
    getData: function(){
     console.log('method vue')
    }
  }

}
</script>

<style lang="scss">

@import 'node_modules/bootstrap/scss/bootstrap.scss';

  body{
     overflow-x: hidden;
  }
</style>
