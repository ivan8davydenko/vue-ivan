<script setup></script>

<template>
  <header>
    <div class="header_content">
      <div class="header_links">
        <a href="#">
          <img src="@/assets/img/location.svg" alt="location" />
          <span>Location</span>
        </a>
        <a href="#">Shop</a>
      </div>
      <div class="header_phone">
        <a href="tel:+79082090500"
          >8 (800) 775-00-70 доб. 3020
          <span style="color: gray">(бесплатно по России)</span>
        </a>
      </div>
    </div>
  </header>
</template>

<style scoped>
header {
  background: #4d4d4d;
}

.header_content {
  height: 44px;
  max-width: calc(1920px - 192px - 192px);
  margin: 0 auto;
  padding: 0 8px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.header_links a,
.header_phone a {
  color: white;
  text-decoration: none;
  display: flex;
  align-items: center;
  gap: 2px;
}

.header_links {
  display: flex;
  align-items: center;
  gap: 12px;
}
</style>
