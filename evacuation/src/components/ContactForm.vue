<template>
  <div class="main-wrapper p-2 p-md-4">
    <div class="container">

      <div class="row">

        <div class="col-12 col-md-7">
          <h1>Служба аварийных комиссаров в Екатеринбурге</h1>
          <ul class="mt-2 mt-md-5">
            <li>Вызов комиссара при ДТП круглосуточно</li>
            <li>Приедем быстро</li>
            <li>Оформим все документы на месте ДТП</li>
            <li>Поможем получить страховое возмещение по ОСАГО</li>
            <li>Сэкономим Ваше время</li>
          </ul>
        </div>

        <div class="col-12 col-md-3 mx-auto contact-bg">
          <h2>Вызвать комиссара</h2>
          <a href="" class="h3">+7 (343) 207-78-38</a>
          <p>Звоните для мгновенного выезда или закажите обратный звонок</p>

          <form>
            <div class="mb-3">
              <input type="email" class="form-control" placeholder="Имя">
            </div>
            <div class="mb-3">
              <input type="password" class="form-control" placeholder="+7 999-999-99-99">
            </div>
            <button type="submit" class="btn btn-primary w-100">Вызвать</button>
          </form>

          <p>Нажимая кнопку "Вызвать" Вы соглашаетесь с условиями обработки персональных данных</p>
        </div>
      </div>

    </div>
  </div>

</template>

<script>
export default {

}
</script>

<style scoped>
.main-wrapper {
  background-image: url("../assets/maing-bg.jpg");
  background-position: center;
  background-size: cover;
  background-repeat: no-repeat;
}
.contact-bg {
  background: rgba(130,130,130,0.5);
  padding: 15px 15px;
}
</style>