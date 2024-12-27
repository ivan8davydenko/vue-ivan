<script setup></script>

<template>
  <main>
    <div class="banner_content">
      <div class="popular_one">
        <h1>Популярные категории</h1>
        <a href="#">
          <img src="@/assets/img/phone.svg" alt="phone" />
          <span>Телефоны и планшеты</span>
        </a>
        <a href="#">
          <img src="@/assets/img/phone.svg" alt="phone" />
          <span>Телефоны и планшеты</span>
        </a>
        <a href="#">
          <img src="@/assets/img/phone.svg" alt="phone" />
          <span>Телефоны и планшеты</span>
        </a>
        <a href="#">
          <img src="@/assets/img/phone.svg" alt="phone" />
          <span>Телефоны и планшеты</span>
        </a>
        <a href="#">
          <img src="@/assets/img/phone.svg" alt="phone" />
          <span>Телефоны и планшеты</span>
        </a>
        <a href="#">
          <img src="@/assets/img/phone.svg" alt="phone" />
          <span>Телефоны и планшеты</span>
        </a>
        <a href="#">
          <img src="@/assets/img/phone.svg" alt="phone" />
          <span>Телефоны и планшеты</span>
        </a>
        <a href="#">
          <img src="@/assets/img/phone.svg" alt="phone" />
          <span>Телефоны и планшеты</span>
        </a>
        <a href="#">
          <img src="@/assets/img/phone.svg" alt="phone" />
          <span>Телефоны и планшеты</span>
        </a>
        <a href="#">
          <img src="@/assets/img/phone.svg" alt="phone" />
          <span>Телефоны и планшеты</span>
        </a>
      </div>
      <div class="popular_two">
        <a href="#">
          <img src="@/assets/img/percent.svg" alt="percent" />
          <span>Уцененные товары</span>
        </a>
      </div>
      <div class="commercial">
        <img src="@/assets/img/commercial.svg" alt="commercial" />
      </div>
      <div class="promotion">
        <h1>Акции</h1>
        <div>
          <img src="@/assets/img/boom.svg" alt="boom" />
          <p>До окончания акции: 18:12:41</p>
        </div>
        <div>
          <img src="@/assets/img/liquidation.svg" alt="liquidation" />
          <p>До окончания акции: 18:12:41</p>
        </div>
        <img src="@/assets/img/ivan.svg" alt="ivan" />
        <p>До окончания акции: 18:12:41</p>
      </div>
    </div>
  </main>
</template>

<style scoped>
.main_content {
  max-width: calc(1920px - 192px - 192px);
  margin: 0 auto;
  display: flex;
  justify-content: space-between;
}

.left_one {
  width: 360px;
  height: 634px;
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 24px;
  border: 1px solid #f2f2f2;
  border-radius: 12px;
  box-shadow: 2px 2px #0000000f;
}

.left_one h2 {
  margin-bottom: 0;
}

.left_two {
  width: 360px;
  height: 80px;
  display: flex;
  justify-content: center;
  margin-top: 20px;
  gap: 13px;
  border: 1px solid #f2f2f2;
  border-radius: 12px;
  box-shadow: 2px 2px #0000000f;
}

.left a {
  display: flex;
  gap: 20px;
  align-items: center;
  text-decoration: none;
  color: black;
}

.right {
  display: flex;
  flex-flow: column wrap;
  width: 1138px;
  height: 730px;
  flex-direction: row;
}

.banner {
  width: 1138px;
  height: 335px;
}

.ivan_and_co {
  width: 1140px;
  height: 363px;
  gap: 20px;
  display: flex;
  justify-content: space-between;
}

.ivan_and_co p {
  padding-left: 20px;
}

.uno {
  width: 360px;
  height: 287px;
  border: 1px solid #f2f2f2;
  border-radius: 12px;
  box-shadow: 1px 1px #0000000f;
}

.dos {
  width: 360px;
  height: 287px;
  border: 1px solid #f2f2f2;
  border-radius: 12px;
  box-shadow: 1px 1px #0000000f;
}

.tres {
  width: 360px;
  height: 287px;
  border: 1px solid #f2f2f2;
  border-radius: 12px;
  box-shadow: 1px 1px #0000000f;
}
</style>
