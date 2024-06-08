<template>
  <!-- Header -->
  <header class="kf-header">

    <!-- topline -->
    <div class="kf-topline">
      <div class="row">
        <div class="col-xs-12 col-sm-6 col-md-4 col-lg-4">

          <!-- hours -->
          <div class="kf-h-group">
            <i class="far fa-clock"></i>
            <em>Horário de atendimento :</em><br> 08:00 da manhã - 09:00 da noite
          </div>

        </div>
        <div class="col-xs-12 col-sm-6 col-md-4 col-lg-4 align-center">

          <!-- social -->
          <div class="kf-h-social">
            <a href="https://www.instagram.com/kafcar.intermediacoes/" target="blank">  @kafcar.intermediacoes</a>
          </div>

        </div>
        <div class="col-xs-12 col-sm-6 col-md-4 col-lg-4 align-right">

          <!-- location -->
          <div class="kf-h-group">
            <i class="fas fa-map-marker-alt"></i>
            <em>Localização :</em> R. Vinte e Dois de Abril, 510 - Estância Pinhais, Pinhais - PR, 83323-205
          </div>

        </div>
      </div>
    </div>

    <!-- navbar -->
    <div class="kf-navbar">
      <div class="row">
        <div class="col-xs-12 col-sm-6 col-md-3 col-lg-3">

          <!-- logo -->
          <div class="kf-logo">
            <a href=""><img src="./src/assets/images/logo.png" alt="" /></a>
          </div>

        </div>
        <div class="col-xs-12 col-sm-6 col-md-6 col-lg-6 align-center">

          <!-- main menu -->
          <div class="kf-main-menu">
            <ul>
              <li><a href="#Inicio">Inicio</a></li>
              <li><a href="#About">Sobre</a></li>
              <li><a href="#Contato">Contato</a></li>
            </ul>
          </div>

        </div>
        <div class="col-xs-12 col-sm-6 col-md-3 col-lg-3 align-right">

          <!-- menu btn -->
          <a href="#" class="kf-menu-btn"><span></span></a>

        </div>
      </div>
    </div>

    <!-- mobile navbar -->
    <div class="kf-navbar-mobile">

      <!-- mobile menu -->
      <div class="kf-main-menu">
        <ul>
          <li class="has-children">
            <a href="#Inicio">Inicio</a>
          </li>
          <li><a href="#About">Sobre</a></li>
          <li><a href="#Contato">Contato</a></li>
        </ul>
      </div>

      <!-- mobile topline -->
      <div class="kf-topline">
        <div class="row">
          <div class="col-xs-12 col-sm-12 col-md-12 col-lg-12">

          </div>
          <div class="col-xs-12 col-sm-12 col-md-12 col-lg-12">


          </div>
          <div class="col-xs-12 col-sm-12 col-md-12 col-lg-12">

            <!-- hours -->
            <div class="kf-h-group">
              <i class="far fa-clock"></i>
              <em>Horário de atendimento :</em><br> 08:00 da manhã - 06:00 da tarde
            </div>

          </div>
          <div class="col-xs-12 col-sm-12 col-md-12 col-lg-12">

            <!-- location -->
            <div class="kf-h-group">
              <i class="fas fa-map-marker-alt"></i>
              <em>Localização :</em> R. Vinte e Dois de Abril, 510 - Estância PinhaisPinhais - PR, 83323-205
            </div>

          </div>
        </div>
      </div>

    </div>

  </header>
</template>

<script>
export default {
  name: "SectionHeader",
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
  max-height: 60px;
}

.kf-btn{
  height: 40px;
  flex-direction: column;
  display: flex;
  justify-content: center;
}

.kf-btn.h-btn {
    margin-left: 90px;
}

.kf-navbar{
  padding: 10px 15px;
  background-color: #090c0f;
}

.kf-header.fixed .kf-navbar {
  background-color: #090c0f;
}

span:after {
  background: white;
}

span::before {
  background: white;
}

.kf-main-menu ul li a {
  color: white;
}

.kf-navbar-mobile:before {
  background-color: 090c0f;
}

.kf-h-social i {
  color: rgb(35, 36, 37);
}
.kf-h-group {
  color: #b99272;
}
.la-angle-down:before {
  color: rgb(35, 36, 37);
}

.kf-main-menu ul li ul{
  background: #ffffff;
}
</style>