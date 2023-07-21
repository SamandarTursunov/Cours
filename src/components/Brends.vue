<template>
  <section class="page__brends brends">
    <div class="brends__container _container">
      <div class="brends__body">
        <div class="brends__part">
          <div class="starts__img">
            <img src="../assets/imgs/main-img/gradient-img.svg" alt="gradient-img">
          </div>
          <div class="starts__post">
            <div class="starts__title brends__title">Партнеры - топовые бренды</div>
          </div>
        </div>
        <div class="brends__partners">
          <img src="../assets/imgs/main-img/brands-img.png" alt="brands">
        </div>
      </div>
    </div>
  </section>
</template>
<style>
.page__brends {
  padding: 0px 0px 180px 0px;
}
.brends__body {
  display: flex;
  flex-direction: column;
  align-content: center;
}
.brends__body > *:not(:last-child) {
  margin-bottom: 89px;
}
.brends__part {
  display: flex;
  align-items: center;
}
.brends__part > *:not(:last-child) {
  margin-right: 20px;
}
</style>