<script setup></script>

<template>
  <nav>
    <div class="navigation_everyone">
      <div class="navigation_one">
        <a href="#">
          <img src="@/assets/img/logo.svg" alt="logo" />
        </a>
        <button>Каталог</button>
      </div>
      <div class="navigation_two">
        <div>
          <a href="#">
            <img
              src="@/assets/img/clock.svg"
              alt="clock"
              style="padding-right: 5px"
            />
            <span>Статус заказа</span>
          </a>
        </div>
        <div>
          <a href="#">
            <img
              src="@/assets/img/graph.svg"
              alt="graph"
              style="padding-right: 5px"
            />
            <span>Сравнение</span>
          </a>
        </div>
        <div>
          <a href="#">
            <img
              src="@/assets/img/hrt.svg"
              alt="hrt"
              style="padding-right: 5px"
            />
            <span>Избранное</span>
          </a>
        </div>
        <div>
          <a href="#">
            <img
              src="@/assets/img/bskt.svg"
              alt="bskt"
              style="padding-right: 5px"
            />
            <span>34 920 Р</span>
          </a>
        </div>
        <div>
          <a href="#">
            <img
              src="@/assets/img/chel.svg"
              alt="chel"
              style="padding-right: 5px"
            />
            <span>Вход | Регистрация</span>
          </a>
        </div>
      </div>
    </div>
  </nav>
</template>

<style scoped>
.navigation_everyone {
  height: 64px;
  max-width: calc(1920px - 192px - 192px);
  margin: 0 auto;
  padding: 0 8px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.navigation_one {
  display: flex;
  align-items: center;
  gap: 20px;
}

.navigation_one button {
  background-color: yellow;
  width: 135px;
  height: 40px;
  border-radius: 6px;
  border: none;
}

.navigation_two {
  display: flex;
  gap: 20px;
}

a {
  text-decoration: none;
  display: flex;
  align-items: center;
}

span {
  color: black;
}
</style>
