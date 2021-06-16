<template>
  <nav class="navbar navbar-expand-lg navbar-dark bg-custom">
  <div class="container">
    <a class="navbar-brand" href="#">Marvin Aguilar</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarScroll" aria-controls="navbarScroll" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarScroll">
      <ul class="navbar-nav ms-auto my-2 my-lg-0 navbar-nav-scroll" style="--bs-scroll-height: 100px;">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#">Acerca de mi</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Educación</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Experiencias</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Skills</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Referencias</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Contacto</a>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" id="navbarScrollingDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            Documentos
          </a>
          <ul class="dropdown-menu" aria-labelledby="navbarScrollingDropdown">
            <li><a class="dropdown-item" href="#">Hoja de Vida</a></li>
            <li><a class="dropdown-item" href="#">Curso Laravel</a></li>
            <!-- <li><hr class="dropdown-divider"></li> -->
            <li><a class="dropdown-item" href="#">Carta de Trabajo</a></li>
            <li><a class="dropdown-item" href="#">Bachillerato</a></li>
          </ul>
        </li>
      </ul>
    </div>
  </div>
</nav>
<div class="p-5 mb-4 bg-light rounded-3 text-center text-color-custom">
      <div class="container-fluid py-5">
        <img src="https://t3.ftcdn.net/jpg/03/46/83/96/360_F_346839683_6nAPzbhpSkIpb8pmAwufkC7c5eD7wYws.jpg" class="img-thumbnail" alt="...">
        <h1 class="display-5 fw-bold">Marvin Aguilar</h1>
        <p class="">Using a series of utilities, you can create this jumbotron, just like the one in previous versions of Bootstrap. Check out the examples below for how you can remix and restyle it to your liking.</p>
        <button class="btn btn-primary btn-lg" type="button">Example button</button>
      </div>
    </div>
</template>

<script>
export default {
    setup () {
        

        return {}
    }
}
</script>

<style lang="scss" scoped>

</style>