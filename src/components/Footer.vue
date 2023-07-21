<template>
  <footer class="footer">
    <div class="footer__container _container">
      <div class="footer__body">
        <div class="study__content footer__content">
          <div class="starts__title">Статьи каждую неделю</div>
          <div class="starts__text">Больше 90% учеников прошли полный курс и смогли <br />собрать свой первый компьютер</div>
        </div>
        <div class="footer__socials">
          <div class="footer__subscribe">
            <input type="email" class="footer__input" placeholder="E-mail">
            <a href="#" class="footer__btn">Подписаться</a>
          </div>
          <div class="footer__links">
            <a href="#" class="footer__link">
              <img src="../assets/imgs/footer-img/1.svg" alt="footer-img">
            </a>
            <a href="#" class="footer__link">
              <img src="../assets/imgs/footer-img/2.svg" alt="footer-img">
            </a>
            <a href="#" class="footer__link">
              <img src="../assets/imgs/footer-img/3.svg" alt="footer-img">
            </a>
            <a href="#" class="footer__link">
              <img src="../assets/imgs/footer-img/4.svg" alt="footer-img">
            </a>
          </div>
          <div class="footer__copy">
            Templates #18. More on Figma.info
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>
<style>
.footer {
  background-image: url("../assets/imgs/main-img/main-bg-img.png");
  background-size: cover;
  background-position: center;
  padding: 0px 0px 30px 0px;
}
.footer__content {
  margin-bottom: 60px;
}
.footer__socials {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}
.footer__subscribe {
  display: flex;
  justify-content: center;
}
.footer__input {
  width: 80%;
  border-radius: 50px 0px 0px 50px;
  opacity: 0.6;
  color: #000;
  background: #fff;
  padding: 10px 20px ;
  outline: none;
}
.footer__btn {
  position: relative;
  z-index: 1;
  font-size: 16px;
  font-weight: 700;
  line-height: 150%;
  padding: 10px 20px ;
  border-radius: 50px;
  color: #fff;
  margin-left: -20px;
  background: linear-gradient(141deg, #DF5950 0%, #451046 100%);
}
.footer__links {
  display: flex;
  margin: 30px 0 30px;
}
.footer__links > *:not(:last-child) {
  margin-right: 30px;
}
.footer__link {
  padding: 13px;
  background: linear-gradient(141deg, #C89AFC 0%, #7C6AFA 100%);
  border-radius: 50%;
}
</style>