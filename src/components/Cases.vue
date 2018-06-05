<template>
  <div class="cases">
      <div class="fondotwo">
			<div class="filter">
				<div class="boxtwo text-center">
					<div class="minititle">
						<div>{{casos}}</div>
						<div class="bgline" style="background:white"></div>
					</div>
					<div class="descrip">{{agradecimiento}}</div>
					<div class="person">{{persona}}</div>
				</div>
			</div>
		</div>
  </div>
</template>
<script>
export default {

   data(){
        return{
            casos:"Casos de éxito",
            agradecimiento:"Gracias a Prestamype logré mudarme a un local más grande en dos oportunidades Incluso contratar más personal para cubrir la demanda. Estoy muy agradecida",
            persona:"GRECIA AGUIRRE"
        }
    }

}
</script>
<style lang="scss">
@import 'node_modules/bootstrap/scss/bootstrap.scss';
   .fondotwo{
		color: #fff !important;
   }
   .filter{
		background-color: rgba(16, 152, 83, 0.89);
   }
   .boxtwo{
				padding:50px 0;
    }
    .minititle{
				font-size: 20px;
        margin-bottom: 25px;
        padding: 0px 15px;
    }
    .bgline{
		height:3px;
		border-radius:30%;
		background:black;
		width:20px;
		margin:0 auto;
		margin-top:30px;
    }
    .descrip{
		margin:50px auto;
		max-width: 850px;
		font-size: 25px;
		font-style: italic;

}
.person{
		font-size: 23px;
		font-weight: 700;
		margin-bottom: 30px;
		line-height: 1.3;

}

</style>

