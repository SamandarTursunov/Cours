<template>
  <section class="page__study study">
    <div class="study__container _container">
      <div class="study__body">
        <div class="study__logo">
          <img src="../assets/imgs/main-img/study-img.svg" alt="icon-logo">
        </div>
        <div class="study__content">
          <div class="starts__title">Программа обучения</div>
          <div class="starts__text">Больше 90% учеников прошли полный курс и смогли <br />собрать свой первый компьютер</div>
        </div>
        <div class="study__statistics statistics">
          <div class="statistics__post-left post-left">
            <div class="post-left__box">
              <div class="post-left__span">Неделя №1</div>
              <h2 class="post-left__title">Красивая часть курса, <br />
              которая помогает в успехе <span class="left_line"></span></h2>
            </div>
            <div class="post-left__box top_box">
              <div class="post-left__span">Неделя №3</div>
              <h2 class="post-left__title">Красивая часть курса, <br />
              которая помогает в успехе <span class="left_line"></span></h2>
            </div>
            <div class="post-left__box top_box">
              <div class="post-left__span">Неделя №5</div>
              <h2 class="post-left__title">Красивая часть курса, <br />
              которая помогает в успехе <span class="left_line"></span></h2>
            </div>
            <div class="post-left__box top_box">
              <div class="post-left__span">Неделя №7</div>
              <h2 class="post-left__title">Красивая часть курса, <br />
              которая помогает в успехе <span class="left_line"></span></h2>
            </div>
          </div>
          <div class="statistics__gradient"></div>
          <div class="statistics__post-right">
            <div class="post-left__box post-right__box">
              <div class="post-left__span post-right__span">Неделя №2</div>
              <h2 class="post-left__title post-right__title">Красивая часть курса, <br />
              которая помогает в успехе <span class="right__line"></span></h2>
            </div>
            <div class="post-left__box post-right__box">
              <div class="post-left__span post-right__span">Неделя №4</div>
              <h2 class="post-left__title post-right__title">Красивая часть курса, <br />
              которая помогает в успехе <span class="right__line"></span></h2>
            </div>
            <div class="post-left__box post-right__box">
              <div class="post-left__span post-right__span">Неделя №6</div>
              <h2 class="post-left__title post-right__title">Красивая часть курса, <br />
              которая помогает в успехе <span class="right__line"></span></h2>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
<style>
.page__study {
  padding: 0px 0px 241px 0px;
}
.study__body,
.study__content {
  display: flex;
  flex-direction: column;
  align-content: center;
  text-align: center;
  justify-content: center;
}
.study__body > *:not(:last-child),
.study__content > *:not(:last-child){
  margin-bottom: 30px;
}
.study__statistics {
  padding: 50px 0px 0px 0px;
}
.statistics {
  display: flex;
  align-items: start;
  justify-content: center;
}
.statistics__post-left {
  padding: 0px 60px 0px 0px;
}
.post-left ,
.post-left__box {
  display: flex;
  flex-direction: column;
}
.post-left__box {
  text-align: right;
}
.post-left__box > *:not(:last-child){
  margin-bottom: 15px;
}
.post-left__span {
  font-size: 16px;
  font-weight: 400;
  line-height: 140%;
  opacity: 0.5;
}
.post-left__title {
  font-size: 18px;
  font-weight: 400;
  line-height: 160%;
  position: relative;
}
.statistics__gradient {
  width: 6px;
  height: 677px;
  background: linear-gradient(142deg, #C89AFC 0%, #7C6AFA 100%);
}
.statistics__post-right {
  padding: 0px 0px 0px 60px;
}
.post-right__box > *:not(:last-child) {
  padding: 87px 0px 0px 0px;
}
.post-right__box {
  text-align: left;
}
.left_line {
  position: absolute;
  width: 40px;
  height: 2px;
  top: 0;
  right: -60px;
  opacity: 0.30000001192092896;
  background: #FFF;
}
.right__line {
  position: absolute;
  width: 40px;
  height: 2px;
  top: 0;
  left: -60px;
  opacity: 0.30000001192092896;
  background: #FFF;
}
.top_box {
  padding: 87px 0px 0px 0px;
}
</style>