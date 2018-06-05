<template>

    <!-- creacion de nuestro component banner -->
    <div class="banner">
        <h1 class="title">{{titulo}} <br/> {{titulo2}} </h1>
        <div class="row bg">
					<div class="col-md-3 offset-md-3 text-center">
								<div class="pres">
								<div><img src="../assets/prestamo.png"></div>
								<a class="abutton prestamo" href="/prestamos" onclick="dataLayer.push({'Interact':true,'Prestamo':true})"><span class="hidden-xs">QUIERO UN </span>PRÉSTAMO</a>
								</div>
					</div>
						<div class="col-md-3 text-center">
								<div class="inv">
								<div><img src="../assets/inversion.png"></div>
								<a class="abutton inversion" href="/invertir" onclick="dataLayer.push({'Interact':true,'Inversion':true})"><span class="hidden-xs">QUIERO </span>INVERTIR</a>
								</div>
						</div>
				</div>
    </div>

</template>

<script>


export default {

    // metodo para crear variables q se usaran en nuestro component

    data(){
        return{
            titulo : 'CONECTAMOS A PERSONAS',
            titulo2: 'PARA QUE CUMPLAN SUS METAS',
            subtitulo : 'Préstamos con garantía hipotecaria',
            subtitutulo:"ffffff"
        }
    },

    // propiedades  mas adelante las varemos

    // props:{
    // //
    // }
}

</script>

<style lang="scss">
    @import 'node_modules/bootstrap/scss/bootstrap.scss';
    .banner{
        height: 500px;
        position: relative;
        text-align: center;
        background-image: url("../assets/banner-home.png");
    }
    .title{
        color: white;
        padding-top: 150px;
        text-transform: uppercase;
        font-size: 40px;
        font-weight: 750;
        letter-spacing: .8px;
    }
    .butbox {
        max-width: 600px;
        margin: 0 auto;
    }

    .pres img {
        height: 65px;
        margin-top: 20px;
    }

    .inv img, .pres img {
        height: 65px;
        margin-top: 20px;
    }
    .pres .abutton {
        background: #01cd78;
    }
     .pres .abutton {
        margin-top: 15px;
        font-size: 18px;
        border: 0;
        width: 85%;
        padding: 10px 0;
        font-weight: 700;
        display: inline-block;
        color: #fff!important;
        text-decoration: none!important;
        cursor: pointer;
        letter-spacing: .2px;
        border-radius: 5px;
    }
    .inv .abutton {
        background: #53a6b4;
    }
    .inv .abutton, .pres .abutton {
        margin-top: 15px;
        font-size: 18px;
        border: 0;
        width: 85%;
        padding: 10px 0;
        font-weight: 700;
        display: inline-block;
        color: #fff!important;
        text-decoration: none!important;
        cursor: pointer;
        letter-spacing: .2px;
        border-radius: 5px;
     }
     .bg{
       margin-left: 0px;
       margin-right: 0px;
     }




</style>
