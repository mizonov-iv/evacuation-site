<template>
  <div class="container d-flex flex-column align-items-center m-0 mt-5">
    <h3 class="text-center">Наша компания осуществляет:</h3>
    <div class="d-flex flex-column flex-md-row justify-content-md-between align-items-center">
      <div class="d-flex flex-column align-items-center align-content-center feedback-item mt-4 col-10 col-md-4 m-md-3">
        <img class="d-block mx-auto rounded-circle w-100" src="../assets/Ellipse_1.png" alt="feedback-1">
        <!-- Button trigger modal -->
        <button type="button" class="btn btn-dark mt-3" data-bs-toggle="modal" data-bs-target="#modal1">
          Помощь в урегулировании убытков
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

      <div class="d-flex flex-column align-items-center align-content-center feedback-item mt-4 col-10 col-md-4 m-md-3">
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
      <div class="d-flex flex-column align-items-center align-content-center feedback-item mt-4 col-10 col-md-4 m-md-3">
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

    <a class="col-7 col-md-3 mx-auto btn btn-outline-dark mt-4" href="tel:+73432077838">Обратиться за помощью</a>
  </div>

<!--  <div class="container d-flex flex-column align-items-center mt-3">-->
<!--    <h3 class="text-center">Ключевые достоинства аварийного комиссара</h3>-->
<!--    <p class="text-center">Экономим Ваше время и берем всю головную боль на себя!</p>-->

<!--    <div class="row mb-3 mx-auto">-->
<!--      <div class="d-flex col-md-5 ">-->
<!--        <div class="about-icon">-->
<!--          <img src="../assets/icons/location.svg" alt="location">-->
<!--        </div>-->
<!--        <p>Оформим документы на месте ДТП</p>-->
<!--      </div>-->

<!--      <div class="d-flex align-items-baseline col-md-5">-->
<!--        <div class="about-icon">-->
<!--          <img src="../assets/icons/magnifier.svg" alt="magnifier">-->
<!--        </div>-->
<!--        <p>Проведем независимую экспертизу</p>-->
<!--      </div>-->

<!--      <div class="d-flex align-items-baseline col-md-5">-->
<!--        <div class="about-icon">-->
<!--          <img src="../assets/icons/people.svg" alt="people">-->
<!--        </div>-->
<!--        <p>Урегулируем споры со страховой</p>-->
<!--      </div>-->

<!--      <div class="d-flex align-items-baseline col-md-5">-->
<!--        <div class="about-icon">-->
<!--          <img src="../assets/icons/photography.svg" alt="photography">-->
<!--        </div>-->
<!--        <p>Проведем фото-фиксацию места ДТП</p>-->
<!--      </div>-->

<!--      <div class="d-flex align-items-baseline col-md-5">-->
<!--        <div class="about-icon">-->
<!--          <img src="../assets/icons/mail.svg" alt="mail">-->
<!--        </div>-->
<!--        <p>Подготовим претензию в страховую</p>-->
<!--      </div>-->

<!--      <div class="d-flex align-items-baseline col-md-5">-->
<!--        <div class="about-icon">-->
<!--          <img src="../assets/icons/car.svg" alt="car">-->
<!--        </div>-->
<!--        <p>Проведем оценку качества ремонта</p>-->
<!--      </div>-->
<!--    </div>-->

<!--    <button class="btn btn-sm btn-outline-success col-8 col-md-2">Заказать звонок</button>-->

<!--  </div>-->

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