<template>
  <nav class="navbar navbar-expand-lg nav-bg">
    <div class="container-fluid">
      <div class="navbar-brand footer__logo mx-auto">
        <img class="d-block w-100" src="../assets/icons/logo.png" alt="">
      </div>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">

          <li class="nav-item">
            <a class="nav-link" aria-current="page" href="#">Цены</a>
          </li>

          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              Услуги
            </a>
            <ul class="dropdown-menu">
              <li><a class="dropdown-item" href="#">Услуга 1</a></li>
              <li><hr class="dropdown-divider"></li>
              <li><a class="dropdown-item" href="#">Услуга 2</a></li>
              <li><hr class="dropdown-divider"></li>
              <li><a class="dropdown-item" href="#">Услуга 3</a></li>
            </ul>
          </li>

          <li class="nav-item">
            <a class="nav-link">О компании</a>
          </li>

          <li class="nav-item">
            <a class="nav-link">Контакты</a>
          </li>

          <li class="nav-item">
            <a class="nav-link">Статьи</a>
          </li>
        </ul>

        <a class="d-block col-5 col-md-2 mx-auto btn btn-outline-dark" href="tel:+73432077838">Позвонить</a>
      </div>
    </div>
  </nav>
</template>

<script>
export default {

}
</script>

<style scoped>
.footer__logo {
  width: 200px;
  height: 45px;
}
.nav-bg {
  background: rgba(130,130,130,0.3);
}
</style>