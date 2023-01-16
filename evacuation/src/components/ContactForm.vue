<template>
  <div class="main-wrapper p-2 p-md-4">
    <div class="container">
      <div class="row">
        <div class="col-12 col-md-7">
          <h1 class="fw-bold text-light display-5">Служба аварийных комиссаров в Екатеринбурге</h1>
          <ul class="mt-2 mt-md-5 list-unstyled text-light fw-bold">
            <li class="mt-1 mt-md-1 fs-4">Вызов комиссара при ДТП круглосуточно</li>
            <li class="mt-1 mt-md-1 fs-4">Приедем быстро</li>
            <li class="mt-1 mt-md-1 fs-4">Оформим все документы на месте ДТП</li>
            <li class="mt-1 mt-md-1 fs-4">Поможем получить страховое возмещение по ОСАГО</li>
            <li class="mt-1 mt-md-1 fs-4">Сэкономим Ваше время</li>
          </ul>
        </div>
        <a class="d-md-none col-9 mx-auto btn btn-danger mb-3 fs-4" href="tel:+73432077838">Обратиться за помощью</a>
        <div class="d-none d-md-block col-md-4 mx-auto contact-bg rounded">
          <h2  class="text-light text-center">Вызвать комиссара</h2>
          <a href="tel:+73432077838" class="d-block fs-3 text-decoration-none text-light text-center">+7 (343) 207-78-38</a>
          <p class="text-light text-center">Звоните для мгновенного выезда или закажите обратный звонок</p>
          <form class="needs-validation" novalidate>
            <div class="mb-3 form-floating has-validation">
              <input
                  type="text"
                  class="form-control"
                  placeholder="Введите имя"
                  v-model="form.name"
                  id="validationUsername"
                  required
              >
              <label for="validationUsername">Ваше имя</label>
              <div class="invalid-feedback">
               Введите имя
              </div>
            </div>
            <div class="mb-3 form-floating has-validation">
              <input
                  type="tel"
                  class="form-control"
                  placeholder="+7 999-999-99-99"
                  v-model="form.phone"
                  v-mask="'+7(###)###-##-##'"
                  id="validationPhone"
                  required
              >
              <label for="validationPhone">Номер телефона</label>
              <div class="invalid-feedback">
                Введите номер телефона
              </div>
            </div>
            <button
                type="submit"
                class="btn btn-primary w-100"
                data-bs-toggle="modal"
                data-bs-target="#exampleModal"
                @click.prevent="sendMessage"
                :disabled="this.form.name === '' || this.form.phone === ''"
            >
              Вызвать
            </button>
          </form>

          <p class="text-light text-center mt-2">Нажимая кнопку "Вызвать" Вы соглашаетесь с условиями обработки персональных данных</p>
        </div>
      </div>

    </div>
    <SuccessPopUp id="exampleModal" aria-labelledby="exampleModalLabel" aria-hidden="true"/>
  </div>

</template>

<script>
import {mask} from "vue-the-mask";
import axios from "axios";
import SuccessPopUp from "@/components/SuccessPopUp";

export default {
  components: {
    SuccessPopUp
  },
  data: () => ({
    form: {
      name: "",
      phone: ""
    },
  }),
  directives: {mask},
  methods: {
    sendMessage() {

      const TOKEN = "5688324213:AAENCPbMFOKejLYK-SN-tITi5io1I6sQJ2I"
      const CHAT_ID = "-1001506049425"
      const URI_API = `https://api.telegram.org/bot${ TOKEN }/sendMessage`

      let message = `<b>Заявка с сайта</b>\n`
      message += `<b>Отправитель: </b> ${this.form.name} \n`
      message += `<b>Телефон: </b> ${this.form.phone}`

      axios.post(URI_API, {
        chat_id: CHAT_ID,
        parse_mode: 'html',
        text: message
      })

      this.form.name = ""
      this.form.phone = ""
    }
  }
}
</script>

<style scoped>
.main-wrapper {
  background-image: url("../assets/bg.jpeg");
  background-position: center;
  background-size: cover;
  background-repeat: no-repeat;
}
.contact-bg {
  background: rgba(130,130,130,0.5);
  padding: 15px 15px;
}
</style>