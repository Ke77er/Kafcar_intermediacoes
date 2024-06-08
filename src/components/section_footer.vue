<template>
<!-- Footer -->
<div class="kf-footer" id="Contato">
	  	<div class="container">
	  		<div class="row">
	  			<div class="col-xs-12 col-sm-12 col-md-6 col-lg-3">

	  				<!-- logo -->
	  				<div class="kf-logo element-anim-1 scroll-animate" data-animate="active">
	  					<a href=""><img src="./src/assets/images/logo.png" alt="" /></a>
	  				</div>

	  			</div>
	  			<div class="col-xs-12 col-sm-12 col-md-6 col-lg-3">

	  				<!-- hours -->
	  				<div class="kf-f-hours element-anim-1 scroll-animate" data-animate="active">
	  					<h5>Horário de Atendimento:</h5>
	  					<ul>
	  						<li>
	  							Segunda - Sabado
	  							<em>08:00 Hrs - 17:00 Hrs</em>
	  						</li>
	  						<li>
	  							<strong>Fechado aos Domingos e Feriados</strong>
	  						</li>
	  					</ul>
	  				</div>

	  			</div>
	  			<div class="col-xs-12 col-sm-12 col-md-6 col-lg-3">

	  				<!-- contact -->
	  				<div class="kf-f-contact element-anim-1 scroll-animate" data-animate="active">
	  					<h5>Contato:</h5>
	  					<ul>
	  						<li>
	  							<i class="las la-map-marker"></i>
	  							<em>Localização :</em>
								R. Vinte e Dois de Abril, 510 - Estância Pinhais, Pinhais - PR, 83323-205
	  						</li>
	  						<li>
	  							<i class="las la-envelope-open-text"></i>
	  							<em>Endereço E-mail :</em>
	  							Kafcarintermediacoes@gmail.com
	  						</li>
	  						<li>
	  							<i class="las la-phone"></i>
	  							<em>Numero de Telefone :</em>
	  							+55 (41) 98505-5056
	  						</li>
	  					</ul>
	  				</div>

	  			</div>
	  			
	  		</div>
	  		<div class="row">
	  			<div class="col-xs-12 col-sm-12 col-md-12 col-lg-12 align-center">

	  				<!-- copyright -->
	  				<div class="kf-copyright element-anim-1 scroll-animate" data-animate="active">
	  					Copyright © 2024 Kafcar Intermediações. Todos os Direitos Reservados.
	  				</div>
	  			</div>
	  		</div>
	  	</div>
	  </div>
</template>

<script>
export default {
  name: "SectionFooter",
  data() {
    return {
    };
  },
  methods: {
  }
}
</script>

<style scoped>

.kf-logo img{
	max-height: 120px;
	max-width: 220px;
}

.row{
	justify-content: center;
}


.kf-footer{
	background-color: #090c0f;
}


.kf-footer h5{
	color: white;
}
.kf-footer li{
	color: white;
}

li:before{
	background: white;
}

.kf-copyright {
	color: white;
}
</style>