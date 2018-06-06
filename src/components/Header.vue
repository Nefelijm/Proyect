<template>
    <!-- creacion de nuestro componnent header
     -->
        <header class="header-dash" id="header">
            <!-- <div class="title-dash">Prestamype</div> -->
            <img class="title-dash" src="../assets/2logo-prestamype-blanco.png" alt="logo">
            <ul class="menu-dash">
                <li>NOSOTROS</li>
                <li>PREGUNTAS FRECUENTES</li>
                <li>ARTICULOS</li>
            </ul>
        </header>
</template>

<script>

    export default {


    }
</script>

<style lang="scss">

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
         width: 200px;

        }

       .menu-dash {
            position: absolute;
            top: 43px;
            right: 20px;
            color:white;

        }
        li{
           display: inline;
           margin-left: 20px;
        }
    }

</style>
