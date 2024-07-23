<template>
  <header class="header">
    <div class="container">
      <div class="contact-info">
        <span>г. Тюмень, улица Мельникайте 72</span>
        <span>Режим работы: пн-пт с 9 до 18</span>
      </div>
      <div class="contact-details">
        <a href="mailto:afan1231231312@inbox.ru">1112312313@inbox.ru</a>
        <div class="social-icons">
          <i class="bi bi-telegram"></i>
          <i class="bi bi-whatsapp"></i>
        </div>
        <a href="tel:+79524884488" class="phone">+7 99999999</a>
        <button type="button" class="btn btn-warning">Обратный звонок</button>
      </div>
    </div>
  </header>
</template>

<script setup lang="ts"></script>

<style scoped>
.header {
  background-color: #000;
  color: #fff;
  padding: 10px 0;
  width: 100%;
  position: fixed;
  top: 0;
  left: 0;
  z-index: 1000; /* Убедиться, что хедер находится поверх остальных элементов */
}

.container {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 0 20px; /* Добавь отступы по бокам для контейнера */
}

.contact-info {
  display: flex;
  flex-direction: column;
}

.contact-details {
  display: flex;
  align-items: center;
}

.contact-details a {
  margin-right: 20px;
}

.social-icons {
  display: flex;
  align-items: center;
  margin-right: 20px;
}

.social-icons i {
  font-size: 24px;
  margin-right: 10px;
  color: #fff;
}

.phone {
  color: #ff0;
  font-weight: bold;
}

.callback-button {
  background-color: #ff0;
  color: #000;
  padding: 5px 10px;
  border: none;
  cursor: pointer;
}
</style>
