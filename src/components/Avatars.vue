<template>
  <section class="page__avatars avatars">
    <div class="avatars__container _container">
      <div class="avatars__body">
        <div class="brends__part">
          <div class="starts__img">
            <img src="../assets/imgs/main-img/avatars-img.svg" alt="avatars-img">
          </div>
          <div class="starts__post">
            <div class="starts__title brends__title">Ваши преподаватели</div>
          </div>
        </div>
        <div class="avatars__users">
          <div class="avatars__user">
            <div class="avatars__img">
              <img src="../assets/imgs/main-img/users/1.png" alt="user">
            </div>
            <h2 class="avatars__title">Дмитрий Иванов</h2>
            <div class="avatars__text">Специалист по видеокартам</div>
            <div class="avatars__btn">
              <a href="#">Биография</a>
            </div>
          </div>
          <div class="avatars__user">
            <div class="avatars__img">
              <img src="../assets/imgs/main-img/users/2.png" alt="user">
            </div>
            <h2 class="avatars__title">Дмитрий Иванов</h2>
            <div class="avatars__text">Специалист по видеокартам</div>
            <div class="avatars__btn">
              <a href="#">Биография</a>
            </div>
          </div>
          <div class="avatars__user">
            <div class="avatars__img">
              <img src="../assets/imgs/main-img/users/3.png" alt="user">
            </div>
            <h2 class="avatars__title">Дмитрий Иванов</h2>
            <div class="avatars__text">Специалист по видеокартам</div>
            <div class="avatars__btn">
              <a href="#">Биография</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
<style>
.page__avatars {
  padding: 0px 0px 200px 0px;
}
.avatars__users {
  display: flex;
  align-items: center;
  justify-content: center;
}
.avatars__users >*:not(:last-child) {
  margin-right: 82px;
}
.avatars__user {
  display: flex;
  flex-direction: column;
  text-align: center;
}
.avatars__user >*:not(:last-child) {
  margin-bottom: 15px;
}
.avatars__img {
  border-radius: 50%;
  margin-bottom: 25px;
}
.avatars__title {
  font-size: 24px;
  font-weight: 400;
  line-height: 140%;
}
.avatars__text {
  font-size: 16px;
  font-weight: 400;
  line-height: 160%;
  opacity: 0.800000011920929;
  margin-bottom: 25px;
}
.avatars__btn a{
  font-size: 16px;
  font-weight: 400;
  line-height: 150%;
  color: #fff;
  padding: 10px 30px;
  border-radius: 50px;
  border: 1px solid #fff;
}
</style>