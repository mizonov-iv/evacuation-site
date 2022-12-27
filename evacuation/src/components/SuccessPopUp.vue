<template>
  <div class="modal" tabindex="-1" >
    <div class="modal-dialog">
      <div class="modal-content">
        <div class="modal-header">
          <h5 class="modal-title">Статус заявки</h5>
          <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
        </div>
        <div class="modal-body">
          <p class="text-center">Заявка успешно отправлена</p>
        </div>
        <div class="modal-footer">
          <button type="button" class="btn btn-outline-dark" data-bs-dismiss="modal">Закрыть</button>
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
.success-modal {
  background: #666666;
  width: 500px;
  position: absolute;
  top: 0;
  left: 0;
}
</style>