<template>
  <section class="menu">
  <div class="container">
    <div class="main-logo">
      <img src="../assets/images/Logo.svg" alt="Logo">
    </div>
    <div class="menu-details">
      <div class="menu-header">
        <div class="row">
          <div class="col-md-8">
            <h2>Monte aqui o seu cardápio. O que está esperando?</h2>
          </div>
          <div class="col-md-4 text-end">
            <div class="btn-wrapper">
              <a href="#" @click="isMenuActive = true">Comida</a>
              <label class="switch">
                <input type="checkbox" checked>
                <span class="slider round"></span>
              </label>
              <a href="#" @click="isMenuActive1 = true">Bebida</a>
            </div>
          </div>
        </div>
      </div>
      <div class="form">
        <div class="form-group">
          <div class="row">
            <div class="col-md-5">
              <input type="text" class="form-control" placeholder="Título do pedido">
            </div>
            <div class="col-md-5">
              <input type="text" class="form-control" placeholder="Sabor">
            </div>
            <div class="col-md-2">
              <input type="text" class="form-control" placeholder="R$">
            </div>
            <div class="col-md-12">
              <div class="form-group">
                <input type="text" class="form-control description" placeholder="Descrição">
              </div>
            </div>
            <div class="col-md-12">
              <div class="upload-picture">
                <div class="btn-wrapper">
                  <a href="#"><i class="fa fa-upload"></i></a>
                  <p>Jogue aqui o arquivo de imagem do seu pastel ou clique para localizar a pasta.</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="register-button-wrapper">
        <a href="#" class="btn-style" @click="isMenuActive = false">LIMPAR</a>
        <a href="#" class="btn-style" @click="isMenuActive = true">CADASTRAR</a>
      </div>
    </div>
  </div>
</section>

  <section class="sub-menu" :class="{'active' : isMenuActive}">
    <h2 class="heading">Veja como será apresentado ao cliente</h2>
    <div class="container">
      <div class="sub-menu-card">
        <div class="sub-menu-card-header">
          <div class="row">
            <div class="col-md-9 col-9">
              <h2 class="name">"Ajeita rapidinho pra mim"</h2>
            </div>
            <div class="col-md-3 col-3 text-end">
              <h2 class="price">R$10,00</h2>
            </div>
          </div>
        </div>
        <ul class="sub-menu-details">
          <li><p><strong>Sabor:</strong>PowerPoint importante</p></li>
          <li><p><strong>Descrição:</strong>1 PPT, 6834 slides e uma pitada de animação</p></li>
        </ul>
        <div class="img-wrapper">
          <img src="../assets/images/pastel-img.png" alt="sa">
        </div>
      </div>
    </div>
  </section>
  <section class="sub-menu" :class="{'active' : isMenuActive1}">
    <h2 class="heading">Veja como será apresentado ao cliente</h2>
    <div class="container">
      <div class="sub-menu-card">
        <div class="sub-menu-card-header">
          <div class="row">
            <div class="col-md-9 col-9">
              <h2 class="name">"Suco de goiaba"</h2>
            </div>
            <div class="col-md-3 col-3 text-end">
              <h2 class="price">R$5,00</h2>
            </div>
          </div>
        </div>
        <ul class="sub-menu-details">
          <li><p><strong>Sabor:</strong>Goiaba</p></li>
          <li><p><strong>Descrição:</strong>Um mero suco de goiaba. Tem sachet de açúcar no balcão...</p></li>
        </ul>
        <div class="img-wrapper">
          <img src="../assets/images/pastel-img1.png" alt="sa">
        </div>
      </div>
    </div>
  </section>

</template>
<script>


export default {
  name: 'HomeView',
  components: {
  },
  data(){
    return{
      isMenuActive: false,
      isMenuActive1: false,
    }
  }
}
</script>
