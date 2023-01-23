<template>
  <div class="container">
    <div class="d-flex flex-column align-items-center m-0 mt-4">
      <p class="text-center display-5 mb-4">Наша компания осуществляет:</p>
      <div class="d-flex flex-column flex-md-row justify-content-md-between align-items-center">
        <div class="d-flex flex-column align-items-center align-content-center feedback-item mt-4 col-10 col-md-4 m-md-2">
          <img class="d-block mx-auto rounded-circle w-100" src="../assets/Ellipse_1.png" alt="feedback-1">
          <!-- Button trigger modal -->
          <button type="button" class="btn btn-dark mt-3" data-bs-toggle="modal" data-bs-target="#modal1">
            Урегулирование убытков
          </button>
        </div>

        <!-- Modal -->
        <div class="modal fade modal-margin" id="modal1" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
          <div class="modal-dialog">
            <div class="modal-content">
              <div class="modal-header">
                <h5 class="modal-title" id="exampleModalLabel">Помощь в урегулировании убытков</h5>
                <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
              </div>
              <div class="modal-body">
                <ul class="list-group mt-1">
                  <li class="list-group-item">Расчет стоимости восстановительного ремонта и величины утраты товарной стоимости транспортного средства</li>
                  <li class="list-group-item">Расчет рыночной стоимости ТС</li>
                  <li class="list-group-item">Расчет годных остатков</li>
                  <li class="list-group-item">Экспертиза качества ремонта</li>
                  <li class="list-group-item">Рецензии</li>
                </ul>
              </div>
              <div class="modal-footer">
                <button type="button" class="btn btn-outline-dark" data-bs-dismiss="modal">Закрыть</button>
              </div>
            </div>
          </div>
        </div>

        <div class="d-flex flex-column align-items-center align-content-center feedback-item mt-4 col-10 col-md-4 m-md-2">
          <img class="d-block mx-auto rounded-circle w-100" src="../assets/Ellipse_2.png" alt="feedback-1">
          <!-- Button trigger modal -->
          <button type="button" class="btn btn-dark mt-3" data-bs-toggle="modal" data-bs-target="#modal2">
            Вызов аварийного комиссара
          </button>
        </div>

        <!-- Modal -->
        <div class="modal fade modal-margin" id="modal2" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
          <div class="modal-dialog">
            <div class="modal-content">
              <div class="modal-header">
                <h5 class="modal-title" id="exampleModalLabel">Вызов службы аварийных комиссаров</h5>
                <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
              </div>
              <div class="modal-body">
                <ul class="list-group mt-1">
                  <li class="list-group-item">Быстрый выезд 24/7</li>
                  <li class="list-group-item">Объективная предварительная оценка ДТП</li>
                  <li class="list-group-item">Цифровая фотосъёмка места происшествия, повреждений и документов</li>
                  <li class="list-group-item">Юридически грамотное составление и оформление документов, сбор справок ГИБДД для страховой компании</li>
                  <li class="list-group-item">Взаимодействие с сотрудниками ГИБДД в спорных случаях</li>
                  <li class="list-group-item">Вызов эвакуатора и техническая помощь</li>
                </ul>
              </div>
              <div class="modal-footer">
                <button type="button" class="btn btn-outline-dark" data-bs-dismiss="modal">Закрыть</button>
              </div>
            </div>
          </div>
        </div>
        <div class="d-flex flex-column align-items-center align-content-center feedback-item mt-4 col-10 col-md-4 m-md-2">
          <img class="d-block mx-auto rounded-circle w-100" src="../assets/Ellipse_3.png" alt="feedback-1">
          <!-- Button trigger modal -->
          <button type="button" class="btn btn-dark mt-3" data-bs-toggle="modal" data-bs-target="#modal3">
            Юридическое сопровождение
          </button>
        </div>

        <!-- Modal -->
        <div class="modal fade modal-margin" id="modal3" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
          <div class="modal-dialog">
            <div class="modal-content">
              <div class="modal-header">
                <h5 class="modal-title" id="exampleModalLabel">Юридическое сопровождение</h5>
                <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
              </div>
              <div class="modal-body">
                <ul class="list-group mt-1">
                  <li class="list-group-item">Взыскание ущерба с виновника ДТП</li>
                  <li class="list-group-item">Защита виновника ДТП</li>
                  <li class="list-group-item">Взыскание материального ущерба при ДТП</li>
                  <li class="list-group-item">Взыскание морального вреда при ДТП</li>
                  <li class="list-group-item">Юридическое представительство в ГИБДД</li>
                  <li class="list-group-item">ВРешение споров со страховыми компаниями</li>
                </ul>
              </div>
              <div class="modal-footer">
                <button type="button" class="btn btn-outline-dark" data-bs-dismiss="modal">Закрыть</button>
              </div>
            </div>
          </div>
        </div>
      </div>
      <a class="d-block col-7 col-md-3 mx-auto btn btn-outline-dark mt-4" href="tel:+73432077838">Обратиться за помощью</a>
    </div>

  </div>

</template>

<script>
export default {

}
</script>

<style scoped>
.about-icon {
  width: 45px;
  margin-right: 20px;
}
.feedback-item__name {
  font-size: 16px;
  line-height: 1.35;
  font-weight: 600;
}
.modal-margin {
  position: fixed;
  top: 10%;
}
</style>