<template>
<div class="footer">
  <div class="greybg text-left">
			<div class="container">
				<div class="boxtwo">
					<div class="row">
						<div class="col-sm-5 foocol">
							<img class="logof" src="https://www.prestamype.com/images/logo-prestamype-blanco.png">
							<p style="margin-top:30px">
               <a href="/nosotros" target="_blank" style="color: #fff !important; border-bottom: 1px solid rgba(255,255,255,0.7); text-decoration: none !important; padding-bottom: 3px;">aquí</a>.</p>
                <p> Prestamype es una marca de P2P Finance Consulting SAC, empresa registrada en la Superintendencia de Banca y Seguros (SBS – Resolución N° 03470). Más detalles <a href="/nosotros" target="_blank">aquí</a></p>
							<div class="icons">
								<div class="icon">
									<div><img src="../assets/icono_direccion_footer.png"></div>
									<p>{{direccion}}<br>{{distrito}}</p>
								</div>
								<div class="icon">
									<div><img src="../assets/icono_correo_footer.png"></div>
									<p>{{informacion}}</p>
								</div>
								<div class="icon">
									<div><img src="../assets/icono_telefono_footer.png"></div>
									<p>(01) 223 - 5912</p>
								</div>
							</div>
						</div>
						<div class="col-sm-3 foocol secondCol">
							<h4>{{mapa}}</h4>
							<div class="info"><a href="/prestamos">Pide tu Préstamo</a></div>
							<div><a href="/invertir">Quiero Invertir</a></div>
							<div><a href="/nosotros">Nosotros</a></div>
              <div><a href="/preguntas-frecuentes">PREGUNTAS FRECUENTES</a></div>
							<div><a href="/articulos">Noticias</a></div>
						</div>
						<div class="col-sm-4 foocol">
							<h4>AVISO LEGAL</h4><br>
							<p>
                Prestamype pone en relación a personas que buscan un préstamo con inversionistas interesados en prestar directamente su capital. Prestamype evalúa los perfiles de los empresarios, elabora el contrato de préstamo con garantía hipotecaria, realiza la gestión del préstamo y el seguimiento hasta el levantamiento de la hipoteca. No realiza intermediación financiera. Los contratos de préstamo son de un periodo de 12, 18 o 24 meses, sin periodo mínimo de cancelación de acuerdo al Código del Consumidor (Ley N° 29571) y pueden ser renovados al final del periodo. Su Tasa Costo Efectivo Anual (TCEA) promedio es de 34%. La TCEA de Prestamype incluye a la tasa de interés y todos los gastos vinculados al préstamo, incluso incluye al levantamiento de la hipoteca.
                A título de comparación, la tasa de interés anual (TEA, que no incluye los gastos) promedio del sistema financiero para créditos a la microempresa en Perú es de 44% (enero 2017).
							</p>
						</div>
					</div>
				</div>
			</div>
		</div>
</div>

</template>
<script>
export default {
  data (){
    return{
      direccion:'Calle Martir Olaya 129 Of 1304',
      distrito:'Miraflores, Lima',
      informacion:'info@prestamype.com',
      mapa:'MAPA DEL SITIO',


    }

  }


}
</script>
<style>
   .greybg{
		background:#2D2D2D;
   }

  .greybg *{
		text-align: left;
		color:white;
   }

.foocol{
		font-weight: 500px;
}

.foocol h4{
		font-weight: 800px;

}
.info{
		margin-top:40px;

}
.icons {
		margin-top: 40px;

}
.icon{
		margin:25px 0;

}
.icon p, .icon div{
		display: inline-block;
		vertical-align:top;

}
.icon div{
		width:40px;

}
.secondCol a{
		display:block;
		margin-bottom:18px;
		text-decoration:none;
		color:white;
		text-transform: uppercase;
}
.secondCol a:hover{
		text-decoration:none;
		color:white;
		cursor:pointer;

}
.greyfont {
		color:#ffffff69 !important;

}
.maxgreybg{
		background:#262626;

}
.maxgreybg p{
		margin:30px 0;
		color:white;

}
.itemg{
		display:inline-block !important;
		margin:0 20px;

}
/* PAGINA EMPRESARIOS
.fondo{
		height:550px;
		position:relative;
}
*/
.blankbg{
		background: #F6F6F6;

}
.blankbg *{
		color: black;

}
.boxemp{
		margin-top:-330px;
}
.whitebk *{
		color:black
}
.whitebk{
		background:white;
		margin-bottom: 50px;
		padding: 10px;
		border-radius: 10px;
		position: relative;
		border: solid 1px #f6f6f6;
      -webkit-transition : border 500ms ease-out;
        -moz-transition : border 500ms ease-out;
          -o-transition : border 500ms ease-out;
            transition : border 500ms ease-out;
}

.noblink{
  border: 3px solid #fff;
}

.blink{
  animation: blink .3s step-end infinite alternate;
}

@keyframes blink {
  50% { border-color: #62d465; }
}

.reps{
		position: absolute;
		bottom:100%;
		right:20px;
}
.reps img{
		max-width:180px;
}
.califica{
		margin: 20px;
}
.califica input, .califica select, .ctainv input{
		background:#F6F6F6;
		border:0;
		margin:0;
		padding:15px;
		width: 100%;
		font-weight: 500;
		text-align:left;
		font-size: 16px;
		-webkit-appearance: none;
		-moz-appearance:    none;
		appearance:         none;
		border-radius: 0px;
    letter-spacing: 0.2px;
    outline: none;
}

.califica select{
		cursor: pointer;
}

.califica input.wrong, .califica select.wrong{
  border: 2px solid #ff0000;
  padding: 13px;
}

.cam{
		position: relative;
    padding: 2px;
}

.cam img{
		position: absolute;
		bottom: 22px;
		right: 20px;
		pointer-events: none;
}

.calc{
		background:#62D465;
		border:0;
		padding:15px 0;
    font-size: 16px;
		width:100%;
		color:white;
		font-weight:bold;
		cursor: pointer;
		margin:10px;
    outline: none;
}

.a-left{
  text-align: left;
}

.greenf{
		color:#62D465;
    margin-bottom: 30px;
    font-size: 27px;
    margin-top: 20px;
}
.bluef{
		color:#7ab0bf;
}
.carac{
    border-radius: 10px;
		background:white;
		height:auto;
		width:100%;
		border:2px solid #F6F6F6;
		border-right:0px;
    padding: 0px 15px;
}
.boxes{
		padding: 50px 80px;
    padding-top: 50px;
    border-radius: 5px;
}
.boxes li{
		text-align: left;
		line-height: 20px;
		margin-bottom: 7px;
		font-weight: 500;
	  line-height: 1.12;
}
.boxes li span{
		font-size: 16px;
		color: #323232;
}
.boxes li a{
		color: #62D465;
		font-weight: 600;
}
.boxes ul{
		margin-top: 20px;
}

.left-border{
  border-left: 3px solid #f9f9f9;
}

.mgbotm{
		margin-bottom: 50px;
}
.coments{
		padding: 80px 0;
		position: relative;
}
/*para arreglar las columnas y filas*/
.fixrow{margin:0}
.fixcol{padding:0}
.otherbox{
		padding: 70px 0px;
}

.otherbox h4{
		font-weight: 800;
		margin: 25px 0px;
		font-size: 20px;

}

.otherbox p{
  font-size: 15px;
  padding: 0px 30px;
  font-weight: 500;
  color: #323232;
  line-height: 1.57;
}

.otimg{
		display: inline-block;
		background: #fff;
		width: 110px;
		height: 110px;
		position: relative;
		text-align: center;
		border-radius: 60px;
}

.otimg img{
		position: absolute;
		left: 50%;
		top: 50%;
		transform: translate(-50%,-50%);
}

.otherbox .linewhite{
		height: 20px;
		width: 75%;
		background: #fff;
		margin: 0 auto;
		position: relative;
		top: 65px;
}

/* :V */

.footer p{
		color: #fff;
		font-weight: 600;
		text-align: left;

}


</style>


