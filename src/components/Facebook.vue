<template>

<div class="facebook">
  <div class="row bgfacebook">
					<div class="col ">
							<div class="greenimg social">
								<div class="container">
									<div class="boxthree text-center">
										<h3 class="titletwo "> SÍGUENOS EN: <a class="faacebook" target="_blank" href="https://www.facebook.com/Prestamype/"><img class="fa-facebook" src="../assets/fa-facebook.png" alt="icon-facebook"></a></h3>
									</div>
								</div>
							</div>
					</div>
	</div>
</div>

</template>
<script>
export default {

}
</script>
<style lang ="scss">
 @import 'node_modules/bootstrap/scss/bootstrap.scss';


  .bgfacebook{
        height:150px;
        position: relative;
        text-align: center;
        background-image: url("../assets/separador.jpg");
  }
 .faacebook {
  width: 53px;
  height: 53px;
  border-radius: 50%;
  padding-top: 13px;
  padding-bottom: 3px;
  font-size: 20px;
  display: inline-block;
  background: #4267b2;
  margin-left: 8px;
  color: #fff!important
}
.fa-facebook{
  width: 10px;
}
.titletwo {
  font-size: 40px;
  font-weight: 700;
  letter-spacing: .3px;
  color: white;
  margin-top:50px;
}

</style>


