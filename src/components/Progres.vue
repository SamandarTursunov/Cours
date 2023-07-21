<template>
  <div class="progres">
    <div class="progres__container _container">
      <div class="progres__boxs">
        <div class="header__btn">
          <a href="#" class="header__link">Заказать курс</a>
        </div>
        <div class="progres__course">
          <div class="progres__text">Учеников всего: <span class="progres__span">200</span></div>
          <div class="progres__text">Успешно закончили курс: <span class="progres__span">190</span></div>
        </div>
        <div class="progres__people people-progres">
          <div class="people-progres__money">Заработано учениками: <span class="progres__span">400 000₽</span></div>
          <div class="people-progres__liner"><span></span></div>
          <div class="people-progres__zero">0 <span class="people-progres__span">1 000 000₽</span></div>
        </div>
      </div>
    </div>
  </div>
</template>
<style>
.progres {
  position: relative;
  z-index: 7;
  padding: 43px 0px 43px 0px;
  background: #121212;
}
.progres__boxs {
  display: flex;
  align-items: center;
  justify-content: center;
}
.progres__boxs > *:not(:last-child) {
  margin-right: 81px;
}
.progres__text,
.people-progres__money, 
.people-progres__zero {
  color: #ffffff48;
  line-height: 170%;
}
.progres__span {
  margin-left: 20px;
  color: #ffff;
}
.people-progres__liner {
  position: relative;
  width: 100%;
  height: 6px;
  background: #ffff;
}
.people-progres__liner span {
  position: absolute;
  background: linear-gradient(142deg, #C89AFC 0%, #7C6AFA 100%);
  width: 440px;
  height: 6px;
  top: 0;
  left: 0;
}
.people-progres__span {
  margin-left: 560px;
}
</style>