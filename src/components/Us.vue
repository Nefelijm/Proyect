<template>
<div class="us">
  <div class="row">
					<div class="col">
							<div class="whitebg">
									<div class="container text-center">
										<div class="boxtwo">
											<div class="minititle">
												<div>{{nosotros}}</div>
												<div class="bgline"></div>
											</div>
											<div class="rowimg">
												<a target="_blank" href="https://gestion.pe/buscar/?query=prestamype"><img src="../assets/gestion-diario.png"></a>
												<a target="_blank" href="https://elcomercio.pe/buscar/?query=prestamype"><img src="../assets/logo-el-comercio.png"></a>
												<a target="_blank" href="http://www.mundoempresarial.pe/search.html?searchword=prestamype&amp;searchphrase=all"><img src="../assets/logo-mundo-empresarial.png"></a>
												<a target="_blank" href="http://larepublica.pe/buscador?buscando=prestamype"><img target="_blank" src="../assets/logo-la-republica.png"></a>
												<a target="_blank" href="http://andina.pe/agencia/busqueda.aspx?search=prestamype"><img src="../assets/logo-andina.png"></a>
												<a target="_blank" href="http://elperuano.pe/busqueda.aspx?claves=prestamype"><img src="../assets/logo-el-peruano.png"></a>
												<a target="_blank" href="https://peru21.pe/buscar/?query=prestamype"><img src="../assets/logo-peru-21.png"></a>
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
            nosotros:"Quienes hablan de nosotros"
        }
    },

}
</script>
<style lang ="scss">
 @import 'node_modules/bootstrap/scss/bootstrap.scss';
    .minititle{
		font-size: 30px;
		font-weight: 500;
		margin-bottom: 40px;
}

.bgline{
		height:3px;
		border-radius:30%;
		background:black;
		width:20px;
		margin:0 auto;
		margin-top:30px;
}

.boxtwo, .boxfun{
		padding:80px 0px;
}
.rowimg{
		margin-bottom:50px;
}
.rowimg img{
		max-width:250px;
		margin:20px
}

</style>


