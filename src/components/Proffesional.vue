<template>
  <section class="page__proffesional">
    <div class="proffesional__container _container">
      <div class="proffesional__body">
        <h2 class="proffesional__title">Получите профессию прямо сейчас</h2>
        <div class="proffesional__contents">
          <div class="proffesional__content">
            <div class="proffesional__icon">
              <img src="../assets/imgs/main-img/icons/1.svg" alt="icon">
            </div>
            <h2 class="proffesional__secondtitle">Только практические <br />навыки в работе</h2>
            <div class="proffesional__text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Netus eget velit quisque accumsan amet tortor. Velit, volutpat egestas fringilla mi porttitor tempus. Placerat dui.</div>  
          </div>
          <div class="proffesional__content">
            <div class="proffesional__icon">
              <img src="../assets/imgs/main-img/icons/2.svg" alt="icon">
            </div>
            <h2 class="proffesional__secondtitle">Работа на самом <br />
            современном оборудовании</h2>
            <div class="proffesional__text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Netus eget velit quisque accumsan amet tortor. Velit, volutpat egestas fringilla mi porttitor tempus. Placerat dui.</div>  
          </div>
          <div class="proffesional__content">
            <div class="proffesional__icon">
              <img src="../assets/imgs/main-img/icons/3.svg" alt="icon">
            </div>
            <h2 class="proffesional__secondtitle">Сертификация <br /> по окончании обучения</h2>
            <div class="proffesional__text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Netus eget velit quisque accumsan amet tortor. Velit, volutpat egestas fringilla mi porttitor tempus. Placerat dui.</div>  
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
<style>
.page__proffesional {
  padding: 0px 0px 230px 0px;
}
.proffesional__body {
  display: flex;
  flex-direction: column;
  align-content: center;
}
.proffesional__body > *:not(:last-child) {
  margin-bottom: 120px;
}
.proffesional__title {
  font-size: 48px;
  font-weight: 700;
  color: #fff;
  line-height: 140%;
  text-align: center;
}
.proffesional__contents {
  display: flex;
  align-items: center;
}
.proffesional__contents > *:not(:last-child){
  margin-right: 82px;
}
.proffesional__content {
  width: 100%;
  height: 100%;
  display: flex;
  flex-direction: column;
  align-content: center;
  justify-content: flex-start;
  text-align: center;
}
.proffesional__content > *:not(:last-child) {
  margin-bottom: 30px;
}
.proffesional__icon {
  margin-bottom: 30px;
  vertical-align: top;
}
.proffesional__secondtitle {
  font-size: 24px;
  font-weight: 400;
  line-height: 140%;
  color: #fff;
}
.proffesional__text {
  font-size: 16px;
  font-weight: 400;
  line-height: 140%;
  opacity: 0.800000011920929;
}
</style>