<template>
    <!-- creacion de nuestro componnent header
     -->
        <header class="header-dash" id="header">
            <!-- <div class="title-dash">Prestamype</div> -->
            <img class="title-dash" src="../assets/2logo-prestamype-blanco.png" alt="logo">
            <ul class="menu-dash">
                <li>Nosotros</li>
                <li>Preguntas frecuentes</li>
                <li>Articulos</li>
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
        box-shadow: 2px 3px 20px 3px #ddd;
        background-color: rgb(46, 44, 44);

       .title-dash{
         margin-right: 20px;
        }

       .menu-dash{
            position: absolute;
            top: 30px;
            right: 20px;
            color:white;
        }
    }

</style>
