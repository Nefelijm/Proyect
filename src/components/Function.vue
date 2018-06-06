<template>
   <div class="function">
      <div class="whitebg text-center">
						<div class="container">
								<div class="boxfun">
									<div  class="minititle">
										<div>{{funciona}}</div>
										<div class="bgline"></div>
									</div>
									<div class="funciona">
										<div class="row rel">
											<div class="flechabox"><img class="flecha" src="../assets/flecha-fintech.png"></div>
											<div class="col-md-4 invisi"><div class="fotoemp"><img src="../assets/empresario.png"></div></div>
											<div class="col-md-4 invisi"></div>
											<div class="col-md-4 invisi"><div class="fotoinv"><img src="../assets/inversionista.png"></div></div>
										</div>
										<div class="row line">
											<div class="col-sm-4 soli">
												<div class="des">
													<div class="subtitle">{{empresario}}</div>
													<p>{{edescription}}</p>
                          <div class="flech"><img src="../assets/flechas.png"></div>
												</div>
											</div>
											<div class="col-sm-4 soli">
												<div class="des whit">
													<div class="subtitle">{{prestamype}}</div>
													<p>{{pdescription}}</p>
                          <div class="flech"><img src="../assets/flechas.png"></div>
												</div>
											</div>
											<div class="col-sm-4 soli">
												<div class="des pull-right">
													<div class="subtitle">{{inversionista}}</div>
													<p>{{idescription}}</p>
												</div>
											</div>
										</div>
									</div>
								</div>
						</div>
			</div>
  </div>

</template>
<script>
export default {

   data(){
        return{
            funciona : 'Cómo funcionaaaaaa',
            empresario:'EMPRESARIO',
            edescription:'Recibe el préstamo que necesita para hacer crecer su negocio',
            prestamype:'PRESTAMYPE',
            pdescription:'Conecta, asesora y gestiona el préstamo con condiciones justas para ambas partes.',
            inversionista:'INVERSIONISTA',
            idescription: 'Rentabiliza mensualmente sus ahorros invirtiendo en proyectos de personas',
        }
    },

}
</script>
<style lang="scss">
  @import 'node_modules/bootstrap/scss/bootstrap.scss';
      .line{
          background-color: rgb(243, 239, 239);
      }

      // .minititle{
      //   // margin-top: 10px;
      //   // font-size: 40px;
      //   // font-weight: 500px;
      //   // margin-bottom:40px;
      //    font-size: 20px;
      //  }

      .bgline {
        height: 3px;
        border-radius: 30%;
        background: #000;
        width: 20px;
        margin: 0 auto;
        margin-top: 30px;
      }
      .flechabox {
        position: absolute;
        bottom: -15px;
       }
      .whitebg {
        background: #fff
      }

      .whitebg * {
        color: #000
      }
      .boxfun,.boxtwo {
        padding: 80px 0
      }

      .fotoemp,
      .fotoinv {
        width: 80%
      }
      .soli {
        padding: 0!important
      }
      .soli p {
        font-size: 15px
      }
      .subtitle {
        font-size: 20px;
        font-weight: 800;
         margin: 20px 0
       }

      .des {
        padding: 10px 40px;
        position: relative
      }

        .flech {
          display: none;
          position: absolute;
          top: 90%;
          z-index: 100;
          left: 0;
          right: 0
        }

       .flech img {
          width: 30px
        }
       .rel {
         position: relative
         }
        .flecha {
         width: 100%;

        }

@media (max-width: 792px){
  //  .minititle{
	// 			font-size: 20px;
  //       margin-bottom: 25px;
  //       padding: 0px 15px;
  // }
  .flecha{
				display:none;
		}
  .flech{
				display:block;
		}
   .invisi{
    display:none;
    }

}



</style>


