<template>
  <section class="page__starts starts">
    <div class="starts__container _container">
      <div class="starts__body">
        <div class="starts__content">
          <div class="starts__img">
            <img src="../assets/imgs/main-img/starts-img.svg" alt="protsessor-img">
          </div>
          <div class="starts__post">
            <div class="starts__title">Быстрый старт</div>
          </div>
        </div>
        <div class="starts__text">Больше 90% учеников прошли полный курс и смогли <br />собрать свой первый компьютер</div>
      </div>
      <div class="starts__static">
        <div class="starts__box">
          <div class="starts__num">100%</div>
          <div class="starts__gradient"></div>
        </div>
        <div class="starts__box">
          <div class="starts__num">75%</div>
          <div class="starts__gradient gradient"></div>
        </div>
        <div class="starts__box">
          <div class="starts__num">50%</div>
          <div class="starts__gradient gradient_one"></div>
        </div>
        <div class="starts__box">
          <div class="starts__num">Итог</div>
          <div class="starts__bg">
            <div class="starts__gradient gradient_two"></div>
          </div>
        </div>
      </div>
      <div class="starts__poster">
        <div class="text-starts">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Netus eget velit quisque accumsan amet tortor. Velit, volutpat egestas fringilla mi porttitor tempus. Placerat dui.</div>
        <div class="text-starts">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Netus eget velit quisque accumsan amet tortor. Velit, volutpat egestas fringilla mi porttitor tempus. Placerat dui.</div>
        <div class="text-starts">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Netus eget velit quisque accumsan amet tortor. Velit, volutpat egestas fringilla mi porttitor tempus. Placerat dui.</div>
      </div>
    </div>
  </section>
</template>
<style>
.page__starts {
  padding: 0px 0px 200px 0px;
}
.starts__body:not(:last-child) {
  margin-bottom: 80px;
}
.starts__body > *:not(:last-child){
  margin-bottom: 20px;
}
.starts__content {
  display: flex;
  align-items: center;
}
.starts__content > *:not(:last-child){
  margin-right: 20px;
}
.starts__title {
  font-size: 48px;
  font-weight: 700;
  line-height: 140%;
  color: #fff;
}
.starts__text {
  font-size: 16px;
  font-weight: 400;
  line-height: 160%;
  opacity: 0.5; 
  color: #fff;
}
.starts__static {
  display: flex;
  align-items: center;
  margin-bottom: 25px;
}
.starts__box {
  display: flex;
  flex-direction: column;
  text-align: start;
  position: relative;
}
.starts__box > *:not(:last-child){
  margin-bottom: 30px;
}
.starts__num {
  color: #fff;
  font-size: 35px;
  font-weight: 700;
  line-height: 140%;
  margin-bottom: 15px
}
.starts__gradient {
  width: 324px;
  height: 80px;
  background: linear-gradient(142deg, #C89AFC 0%, #7C6AFA 100%);
}
.gradient {
  width: 324px;
  height: 60px;
  background: linear-gradient(142deg, #7C6AFA 0%, #C89AFC 100%);
}
.gradient_one {
  width: 324px;
  height: 30px;
  background: linear-gradient(142deg, #C89AFC 0%, #7C6AFA  100%);
}
.gradient_two {
  width: 324px;
  height: 10px;
  background: linear-gradient(142deg, #7C6AFA 0%, #C89AFC 100%);
}
.starts__poster {
  display: flex; 
  align-items: center;

}
.starts__poster > *:not(:last-child) {
  margin-right: 20px;
}
.text-starts {
  color: #fff;
  font-size: 16px;
  font-weight: 400;
  line-height: 160%;
  opacity: 0.5;
}
</style>