<template>
    <!-- creacion de nuestro componnent header
     -->
        <header class="header-dash" id="header">
          <nav>
            <a href=""><img class="title-dash" src="../assets/2logo-prestamype-blanco.png" alt="logo"></a>
            <ul class="menu-dash">
              <b>
                <a class="linea" href=""><li>NOSOTROS</li></a>
                <a class="linea" href=""><li>PREGUNTAS FRECUENTES</li></a>
                <a class="linea" href=""><li>ARTICULOS</li></a>
              </b>
            </ul>
           </nav>
           <!-- <nav class="nav-2">
            <a href=""><img class="title-dash" src="../assets/2logo-prestamype-blanco.png" alt="logo"></a>
            <ul class="menu-dash">
              <b>
                <a href=""><li>NOSOTROS</li></a>
                <a href=""><li>PREGUNTAS FRECUENTES</li></a>
                <a href=""><li>ARTICULOS</li></a>
              </b>
            </ul>
           </nav> -->
        </header>
</template>

<script>

    export default {


    }
</script>

<style lang="scss">
 @import 'node_modules/bootstrap/scss/bootstrap.scss';
    .header-dash{
        height: 70px;
        width: 100%;
        background-color: red;
        position: absolute;
        top: 30px;
        z-index: 1;

       .title-dash{
         margin-left: 90px;
         margin-top: 28px;
         width: 180px;

        }
       .menu-dash {
            position: absolute;
            top: 43px;
            right: 20px;
            color:white;

        }
        .linea{
          text-decoration: none;
        }
        li:hover {
           color: #0067a3 !important;
        }
        li {
           display: inline;
           margin-left: 20px;
           margin-right: 30px;
           font-size: 15px;
           border-color: transparent;
           color: white;
        }
    }

</style>
