<script setup></script>

<template>
  <main>
    <div class="main_content">
      <div class="left">
        <div class="left_one">
          <div>
            <h2>Популярные категории</h2>
          </div>
          <a href="#" v-for="item in 8" :key="item.id">
            <img src="@/assets/img/phone.svg" alt="phone" />
            <span>Телефоны и планшеты</span>
          </a>
        </div>
        <div class="left_two">
          <a href="#">
            <img src="@/assets/img/percent.svg" alt="percent" />
            <span>Уцененные товары</span>
          </a>
        </div>
      </div>
      <div class="right">
        <div class="banner">
          <img src="@/assets/img/commercial.svg" alt="commercial" />
        </div>
        <div>
          <h1>Акции</h1>
          <div class="ivan_and_co">
            <div class="uno">
              <img src="@/assets/img/boom.svg" alt="boom" />
              <p>До окончания акции: 18:12:41</p>
            </div>
            <div class="dos">
              <img src="@/assets/img/liquidation.svg" alt="liquidation" />
              <p>До окончания акции: 18:12:41</p>
            </div>
            <div class="tres">
              <img src="@/assets/img/ivan.svg" alt="ivan" />
              <p>До окончания акции: 18:12:41</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </main>
</template>

<style scoped>
.main_content {
  max-width: calc(1920px - 192px - 192px);
  margin: 0 auto;
  display: flex;
  gap: 12px;
}

.popular_one {
  width: 300px;
  height: 634px;
  border-radius: 12px;
  border: 1px;
  padding-top: 24px;
  padding-left: 42px;
  display: flex;
  flex-direction: column;
  border-style: solid;
  border-color: #f2f2f2;
  box-shadow: 2px 2px #0000000f;
  gap: 24px;
}

.popular_one a {
  text-decoration: none;
  color: black;
  display: flex;
  align-items: center;
  gap: 5px;
}

.popular_one h2 {
  margin-bottom: 0;
  margin-top: 0;
}

.popular_two {
  width: 275px;
  height: 60px;
  border-radius: 12px;
  border: 1px;
  padding-top: 24px;
  padding-right: 27px;
  padding-left: 42px;
  display: flex;
  flex-direction: column;
  border-style: solid;
  border-color: #f2f2f2;
  box-shadow: 2px 2px #0000000f;
  gap: 24px;
  margin-top: 20px;
}

.popular_two a {
  text-decoration: none;
  color: black;
  display: flex;
  align-items: center;
  gap: 5px;
}

.commercial {
  position: absolute;
  top: 12.5%;
  right: 10%;
}

/* h1 {
  position: absolute;
  top: 52%;
  right: 65%;
} */

.promotion_1 {
  position: absolute;
  top: 61.5%;
  right: 51%;
  box-shadow: 5px 5px #00000014;
  border-radius: 12px;
}

.promotion_2 {
  position: absolute;
  top: 61.5%;
  right: 30%;
  box-shadow: 5px 5px #00000014;
  border-radius: 12px;
}

.promotion_3 {
  position: absolute;
  top: 61.5%;
  right: 9%;
  box-shadow: 5px 5px #00000014;
  border-radius: 12px;
}

p {
  display: flex;
  justify-content: center;
  /* display: flex;
  justify-content: space-between; */
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
  /* width: 1138px;
  height: 730px; */
}

.banner {
  /* width: 1138px;
  height: 335px; */
}

.ivan_and_co {
  /* width: 1140px;
  height: 363px; */
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
