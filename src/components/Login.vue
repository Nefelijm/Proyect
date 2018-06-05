<template>
   <div class="login text-right">
      <a class="signin">{{ingresar}}</a>
     	<a class="logo-facebook" href="https://www.facebook.com/Prestamype/" target="_blank" alt="facebook">
	    <img src="../assets/1facebook.png">
	    </a>
   </div>

</template>
<script>
export default {

   data(){
        return{
            ingresar : 'INGRESAR',
        }
    },

}
</script>
<style lang="scss">
  @import 'node_modules/bootstrap/scss/bootstrap.scss';

    .login {
      font-size: 12px;
      background: #000;
      padding: 5px 0;
      color: #fff;
      padding-right: 100px;
      padding-left: 15px;
      margin-right: auto;
      margin-left: auto;
    }


    .text-right {
      text-align: right;
    }

    .signin {
      color: #fff!important;
      text-decoration: none!important;
      cursor: pointer;
      font-weight: 750;
      position: relative;
      top: 2px;
      letter-spacing: .2px;
      margin-right: 2%;
    }
</style>


