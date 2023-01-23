<template>
  <div class="container d-flex flex-column align-items-center mt-5">
    <p class="text-center display-5">Отзывы о работе</p>
    <div class="d-flex flex-column flex-md-row flex-md-wrap align-items-center align-items-md-baseline">
      <div class="d-flex flex-column align-items-center mt-4 col-10 col-md-6">
        <img class="feedback-item__img d-block mx-auto rounded-circle" src="../assets/feddback1.jpeg" alt="feedback-1">
        <p class="feedback-item__name text-center mt-2">Евгений</p>
        <p class="feedback-item__subheader text-center">Все детально и доходчиво разъяснялось</p>
        <p class="feedback-item__description text-center">
          Обратился в авангард  по поводу независимой экспертизы авто, после сильного ДТП в октябре 2022 года.
          Первое ДТП, в данном вопросе "реальный чайник". Сергей приехал, сделал фото - видео,все детали заметил показал мне (которые я кстати не замечал).
          Потом вторичный осмотр в сервисе.
          Отчет, был готов очень быстро. Параллельно, мне были объяснены все дальнейшие этапы, по страховой, суду, жалобам.
          Буквально загружал вопросами, но мне, все детально и доходчиво разъяснялось.
          Спасибо большое, ребят.
        </p>
      </div>
      <div class="d-flex flex-column align-items-center mt-4 col-10 col-md-6">
        <img class="feedback-item__img d-block mx-auto rounded-circle" src="../assets/feddback2.jpeg" alt="feedback-1">
        <p class="feedback-item__name text-center mt-2">Дмитрий</p>
        <p class="feedback-item__subheader text-center">Все было максимально комфортно</p>
        <p class="feedback-item__description text-center">
          В августе 2022 года в попал в ДТП с участием общественного транспорта.
          Вина была на втором участнике.
          Я очень сильно испугался за штрафы.
          Ведь это общественный транспорт и все такое.
          Приятель посоветовал обратиться в Авангард.
          Ребята быстро приехали, всё сделали, составили все документы, всё рассказали, ещё и скидку сделали, я думал это будет стоить очень дорого.
          Однако всё было максимально комфортно и приятно удивлен.
        </p>
      </div>
      <div class="d-flex flex-column align-items-center mt-4 col-10 col-md-4">
        <img class="feedback-item__img d-block mx-auto rounded-circle" src="../assets/feddback3.jpg" alt="feedback-1">
        <p class="feedback-item__name text-center mt-2">Сергей</p>
        <p class="feedback-item__subheader text-center">Время заполнения и цены</p>
        <p class="feedback-item__description text-center">
          Оформлял страховку через Авангард. После ДТП сразу позвонил им, быстро оформили европротокол и оценили ущерб.
        </p>
      </div>
      <div class="d-flex flex-column align-items-center mt-4 col-10 col-md-4">
        <img class="feedback-item__img d-block mx-auto rounded-circle" src="../assets/feddback4.jpg" alt="feedback-1">
        <p class="feedback-item__name text-center mt-2">Ольга</p>
        <p class="feedback-item__subheader text-center">Помогли оформить ДТП</p>
        <p class="feedback-item__description text-center">
          Растерялась после аварии, знакомые посоветовали обратиться в Авангард. Комиссар Сергей помог составить документы и подать заявление в страховую! Уже ждем выплату, очень благодарна!
        </p>
      </div>
      <div class="d-flex flex-column align-items-center mt-4 col-10 col-md-4">
        <img class="feedback-item__img d-block mx-auto rounded-circle" src="../assets/feddback5.jpg" alt="feedback-1">
        <p class="feedback-item__name text-center mt-2">Валерий</p>
        <p class="feedback-item__subheader text-center">Надежно и быстро</p>
        <p class="feedback-item__description text-center">
          Приехали НОЧЬЮ и оформили ДТП. В ГАИ были до момента, пока не получили справку!
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.feedback-item__img {
  width: 130px;
  height: 130px;
}
.feedback-item__name {
  font-size: 16px;
  line-height: 1.35;
  font-weight: 600;
}
.feedback-item__subheader {
  font-size: 14px;
  color: #666;
}
.feedback-item__description {
  font-size: 14px;
  line-height: 1.35;
  font-weight: 600;
}
</style>