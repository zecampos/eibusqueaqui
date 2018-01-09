<template lang="html">
  <div class="container-fluid">
    <div class="fixed-top">
      <div style="margin: 0px 0px 0px 0px"class="row align-items-center ">
        <div class="col-md-12 ">
          <nav class="navbar navbar-light bg-light row justify-content-center">
            <div style=" margin-right: 10px;" class="form-group col-2 ">
              <a  class="navbar-brand" href="#">
                <img src="../../assets/img/logo.png"  class="d-inline-block align-top" alt="">
              </a>
            </div>
            <div class="col-md-6">
              <form class="navbar-form " role="search">
                <div class=" input-group input-group-lg">
                  <span class="input-group-addon" id="sizing-addon1"><img style="width: 60%;" src="../../assets/icon/search.png"  /></span>
                  <input  autocomplete="off" type="text" class="form-control" placeholder="O que você está precisando encontrar?" name="q">
                </div>
              </form>
            </div>
            <div style="margin: 0px 0px 0px 0px"  class="col-md-1 ">
              <div class="col-md-1 ">
                <a href=""><button style="background-color: #f68d3d; color: white; border-radius: 22.5px; letter-spacing: 2px; " type="button" class="btn ">Anuncie aqui</button></a>
              </div>
            </div>
            <div style="margin: 0px 0px 0px 70px" class="col-md-1 ">
              <div class="col-md-1">
                <a href=""><img src="../../assets/icon/facebook.png"/></a>
              </div>
            </div>
          </nav>
        </div>
      </div>
      <nav class="navbar navbar-expand-lg navbar-dark justify-content-center">
        <div class="row align-items-center ">
          <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav mr-auto">
              <li class="nav-item active ">
                <a class="nav-link " href="#"> <img class="icon-header" src="../../assets/icon/academia.png" /> Academias </a>
              </li>
              <li class="nav-item active">
                <a class="nav-link" href="#" > <img class="icon-header" src="../../assets/icon/alimentacao.png" /> Alimentação</a>
              </li>
              <li class="nav-item active">
                <a class="nav-link" href="#"> <img class="icon-header" src="../../assets/icon/roupas.png" /> Vestuários</a>
              </li>
              <li class="nav-item active">
                <a class="nav-link" href="#"> <img class="icon-header" src="../../assets/icon/carro.png" /> Veiculos</a>
              </li>
              <li class="nav-item active">
                <a class="nav-link" href="#"> <img class="icon-header" src="../../assets/icon/saude.png" /> Saúde</a>
              </li>
              <li class="nav-item active">
                <a class="nav-link" href="#"> <img class="icon-header" src="../../assets/icon/servicos.png" /> Serviços Diversos</a>
              </li>
              <li class="nav-item active">
                <a class="nav-link" href="#"> <img class="icon-header" src="../../assets/icon/mais.png" /> Mais Categorias</a>
              </li>
            </ul>
          </div>
        </div>
      </nav>
    </div>
  </div>
</template>

<script>
export default {
}
</script>

<style lang="css">


nav{
    background-color: #f68d3d;
}

@charset "UTF-8";

@font-face {
  font-family: "untitled-font-1";
  src:url("/assets/fonts/untitled-font-1.eot");
  src:url("/assets/fonts/untitled-font-1.eot?#iefix") format("embedded-opentype"),
    url("/assets/fonts/untitled-font-1.woff") format("woff"),
    url("/assets/fonts/untitled-font-1.ttf") format("truetype"),
    url("/assets/fonts/untitled-font-1.svg#untitled-font-1") format("svg");
  font-weight: normal;
  font-style: normal;

}

[data-icon]:before {
  font-family: "untitled-font-1" !important;
  content: attr(data-icon);
  font-style: normal !important;
  font-weight: normal !important;
  font-variant: normal !important;
  text-transform: none !important;
  speak: none;
  line-height: 1;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

[class^="icon-"]:before,
[class*=" icon-"]:before {
  font-family: "untitled-font-1" !important;
  font-style: normal !important;
  font-weight: normal !important;
  font-variant: normal !important;
  text-transform: none !important;
  speak: none;
  line-height: 1;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  font-size: 24px !important;
  vertical-align: middle;
}

.icon-barbell:before {
  content: "\61";
}
.icon-food:before {
  content: "\62";
}
.icon-t-shirt:before {
  content: "\63";
}
.icon-car:before {
  content: "\64";
}
.icon-medkit:before {
  content: "\65";
}
.icon-server:before {
  content: "\66";
}
.search-box{
  position: absolute;
  z-index: 1;
  width: 100%;

  max-height: 500px;
  background-color: white;
  overflow-y: auto;
}
.state{
  padding: 10px;
  color: #f68d3d;
  font-family: sans-serif;

}
.state:hover{
  background:#FFE2CE;
  font-weight: bold;
}

agm-map {
  height: 800px;
}
img{
  max-width: 200px;

}
.icon-header{
  max-height: 20px;

}





</style>
