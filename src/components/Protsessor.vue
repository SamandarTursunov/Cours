<template>
<section class="page__protsessor protsessor">
  <div class="protsessor__container _container">
    <div class="protsessor__body">
      <div class="protsessor__img">
        <img src="../assets/imgs/main-img/protsessor-img.png" alt="protsessor-img">
      </div>
      <div class="protsessor__post">
        <div class="protsessor__title">Чем мы занимаемся?</div>
        <div class="protsessor__text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Eget neque, dignissim et feugiat elit augue in suspendisse egestas. Dictum vestibulum mi et sed nunc, orci fermentum vestibulum, morbi. Et neque,  </div>
      </div>
    </div>
  </div>
</section>
</template>
<style>
.page__protsessor {
  padding: 200px 0px 200px 0px;
}
.protsessor__body {
  display: flex;
  align-items: center;
}
.protsessor__body > *:not(:last-child) {
  margin-right: 139px;
}
.protsessor__title {
  color: #ffff;
  font-size: 48px;
  font-weight: 700;
  line-height: 140%;
}
.protsessor__text {
  color: #ffff;
  font-size: 16px;
  font-weight: 400;
  line-height: 160%;
}
</style>
