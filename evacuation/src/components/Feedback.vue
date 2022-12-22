<template>
  <div class="container d-flex flex-column align-items-center mt-5">
    <h3 class="text-center">Отзывы о работе</h3>
    <div class="d-flex flex-column flex-md-row align-items-center align-items-md-baseline">
      <div class="d-flex flex-column align-items-center feedback-item mt-4 col-10 col-md-4">
        <img class="feedback-item__img d-block mx-auto rounded-circle" src="../assets/feddback1.jpg" alt="feedback-1">
        <p class="feedback-item__name text-center mt-2">Сергей</p>
        <p class="feedback-item__subheader text-center">Время заполнения и цены</p>
        <p class="feedback-item__description text-center">Оформлял страховку через Авангард. После ДТП сразу позвонил им, быстро оформили европротокол и оценили ущерб.</p>
      </div>
      <div class="d-flex flex-column align-items-center feedback-item mt-4 col-10 col-md-4">
        <img class="feedback-item__img d-block mx-auto rounded-circle" src="../assets/feddback2.jpg" alt="feedback-1">
        <p class="feedback-item__name text-center mt-2">Ольга</p>
        <p class="feedback-item__subheader text-center">Помогли оформить ДТП</p>
        <p class="feedback-item__description text-center">Растерялась после аварии, знакомые посоветовали обратиться в Авангард. Комиссар Сергей помог составить документы и подать заявление в страховую! Уже ждем выплату, очень благодарна!</p>
      </div>
      <div class="d-flex flex-column align-items-center feedback-item mt-4 col-10 col-md-4">
        <img class="feedback-item__img d-block mx-auto rounded-circle" src="../assets/feddback3.jpg" alt="feedback-1">
        <p class="feedback-item__name text-center mt-2">Валерий</p>
        <p class="feedback-item__subheader text-center">Надежно и быстро</p>
        <p class="feedback-item__description text-center">Приехали НОЧЬЮ и оформили ДТП. В ГАИ были до момента, пока не получили справку!</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.feedback-item {

}
.feedback-item__img {
  width: 120px;
  height: 120px;
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