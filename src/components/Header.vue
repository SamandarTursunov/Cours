<template>
  <header class="header">
    <div class="header__container">
      <div class="header__logo">
        <img src="../assets/imgs/header-logo.png" alt="header-logo">
      </div>
      <div class="_container">
        <nav class="header__menu">
          <ul class="header__lists">
            <li class="header__list">
              <a href="#">Главная</a>
            </li>
            <li class="header__list">
              <a href="#">Курсы</a>
            </li>
            <li class="header__list">
              <a href="#">Расписание</a>
            </li>
            <li class="header__list">
              <a href="#">Преподаватели</a>
            </li>
            <li class="header__list">
              <a href="#">Рассылка</a>
            </li>
            <li class="header__list">
              <a href="#">Контакты</a>
            </li>
          </ul>
        </nav>
      </div>
      <div class="header__btn">
        <a href="#" class="header__link">Зайти в кабинет</a>
      </div>
    </div>
    <div class="header__body">
      <div class="_container">
        <div class="header__times">
          <div class="header__title">Первый курс <br />по компьютерной сборке</div>
          <div class="header__timer timer-header">
            <div class="timer-header__box">18 <span class="header__span">Дней</span></div>
            <div class="timer-header__box">18 <span class="header__span">Часов</span></div>
            <div class="timer-header__box">18 <span class="header__span">Минут</span></div>
            <div class="timer-header__box">18 <span class="header__span">Секунд</span></div>
          </div>
        </div>
      </div>
    </div>
  </header>
</template>

<style>
.header {
  padding-bottom: 218px;
  background-image: url("../assets/imgs/header__bg-img.png");
  background-size: cover;
  background-position: center;
}
.header__container {
  display: flex;
  justify-content: space-evenly;
  align-items: center;
  padding: 48px 80px 198px;
  position: relative;
  z-index: 10;
}
.header__lists {
  display: flex;
  align-items: center;
}
.header__lists > *:not(:last-child){
  margin-right: 56px;
}
.header__list a{
  color: #ffff;
  list-style: 150%;
}
.header__link {
  color: #ffff;
  padding: 10px 30px;
  border-radius: 50px;
  background: linear-gradient(142deg, #C89AFC 0%, #7C6AFA 100%);
}
.header__times {
  display: flex;
  flex-direction: column;
  align-content: center;
}
.header__times > *:not(:last-child) {
  margin-bottom: 50px;
}
.header__title {
  color: #ffff;
  font-size: 64px;
  line-height: 140%;
  font-weight: 700;
  text-align: left;

}
.header__timer > *:not(:last-child){
  margin-right: 30px;
}
.timer-header {
  display: flex;
  align-items: center;
}
.timer-header__box {
  color: #ffff;
  text-align: center;
  padding: 10px 20px;
  background: #121212;
  font-size: 34px;
  font-weight: 700;
  line-height: 140%;
}
.header__span {
  display: block;
  color: #ffff;
  font-size: 16px;
  font-weight: 400;
  opacity: 0.4000000059604645;
  margin-top: -15px;
}
</style>