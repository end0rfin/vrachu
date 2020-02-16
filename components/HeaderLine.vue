<template>
  <div class="header-line">
    <div class="container">
      <div class="header-line--left-side">
        Портал непрерывного медицинского и фармацевтического образования
      </div>
      <div class="header-line--middle-side">
        <div class="top-phone">
          <div class="top-phone--text">
            Бесплатный звонок
          </div>
          <div class="top-phone--phone">
            8 (800) 545 432
          </div>
        </div>
      </div>
      <div class="header-line--right-side">
        <ul class="header-line--menu">
          <li class="header-line--menu-item"><a href="#about-id">О портале</a></li>
          <li class="header-line--menu-item"><a href="#faq-id">Вопросы и ответы</a></li>
          <li class="header-line--menu-item"><a href="#comments-id">Отзывы</a></li>
        </ul>
      </div>
    </div>
  </div>
</template>


<style>
  @import "../assets/styles/container.css";

  .header-line {
    display: block;

    width: 100%;
    height: 107px;
    background: #FF7300;
    color: #fff;
    padding: 22px 0;

    font-style: normal;
    font-weight: 500;
    font-size: 20px;
    line-height: 23px;
  }
  .header-line--left-side, .header-line--middle-side, .header-line--right-side {
    width: 490px;
    margin-right: 30px;
    text-align: left;
  }
  .header-line--middle-side {
    text-align: center;
  }
  .header-line--right-side {
    text-align: right;
    margin-right: 0;
  }
  .top-phone--text {
    font-size: 20px;
    line-height: 23px;
  }
  .top-phone--phone {
    font-weight: bold;
    font-size: 30px;
    line-height: 35px;
  }

  .header-line--menu {
    display: flex;
    flex-direction: column-reverse;

    width: 100%;

  }
  .header-line--menu-item {
    display: flex;
    width: auto;
  }
</style>
