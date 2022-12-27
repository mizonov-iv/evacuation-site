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

          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              Услуги
            </a>
            <ul class="dropdown-menu">
              <li>
                <a class="dropdown-item" role="button" data-bs-toggle="modal" data-bs-target="#modal1">
                  Помощь в урегулировании убытков
                </a>
              </li>
              <li><hr class="dropdown-divider"></li>
              <li>
                <a class="dropdown-item" role="button" data-bs-toggle="modal" data-bs-target="#modal2">
                  Вызов аварийного комиссара
                </a>
              </li>
              <li><hr class="dropdown-divider"></li>
              <li>
                <a class="dropdown-item" role="button" data-bs-toggle="modal" data-bs-target="#modal3">
                  Юридическое сопровождение
                </a>
              </li>
            </ul>
          </li>

          <li class="nav-item">
            <div role="button" class="nav-link" data-bs-toggle="modal" data-bs-target="#modalAbout">О компании</div>
          </li>
          <!-- Modal -->
          <div class="modal fade modal-margin" id="modalAbout" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
            <div class="modal-dialog">
              <div class="modal-content">
                <div class="modal-header">
                  <h5 class="modal-title" id="exampleModalLabel">О компании</h5>
                  <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                </div>
                <div class="modal-body">
                  <p>
                    Мы знаем множество нюансов работы со страховыми компаниями, что позволяет аварийным комиссарам компании Авангард быстро оценить стоимость ущерба, правильно оформить все документы и увеличить шансы на получение страховой выплаты!
                  </p>
                </div>
                <div class="modal-footer">
                  <a class="d-block btn btn-outline-dark" href="tel:+73432077838">Позвонить</a>
                  <a class="btn btn-outline-dark" data-bs-dismiss="modal">Закрыть</a>

                </div>
              </div>
            </div>
          </div>

          <li class="nav-item">
            <div role="button" class="nav-link" data-bs-toggle="modal" data-bs-target="#modalContact">Контакты</div>
          </li>
        </ul>

        <div class="modal fade modal-margin" id="modalContact" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
          <div class="modal-dialog">
            <div class="modal-content">
              <div class="modal-header">
                <h5 class="modal-title" id="exampleModalLabel">Наши контакты</h5>
                <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
              </div>
              <div class="modal-body">
                <div class="h6 text-center mt-2">
                  <p class="fw-bold m-0 mb-2">Телефон</p>
                  <a class="fw-light text-decoration-none" href="tel:+73432077838">+7 (343) 207-78-38</a>
                </div>
                <div class="h6 text-center m-0 mt-2">
                  <p class="fw-bold m-0 mb-2">E-mail</p>
                  <a class="fw-light text-decoration-none" href="mailto:info@avangard196.ru">info@avangard196.ru</a>
                </div>
                <div class="h6 text-center m-0 mt-2">
                  <p class="fw-bold m-0 mb-2">Адрес</p>
                  <p class="fw-light m-0">Блюхера 58, офис 401</p>
                  <p class="fw-light m-0">Титова 27/3, офис 102</p>
                  <p>Екатеринбург</p>
                </div>
                <div class="h6 text-center m-0 mt-2">
                  <p class="fw-bold m-0 mb-2">Режим работы</p>
                  <p class="fw-light m-0">09:00 до 18:00</p>
                </div>
              </div>
              <div class="modal-footer">
                <a class="d-block btn btn-outline-dark" href="tel:+73432077838">Позвонить</a>
                <a class="btn btn-outline-dark" data-bs-dismiss="modal">Закрыть</a>

              </div>
            </div>
          </div>
        </div>

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