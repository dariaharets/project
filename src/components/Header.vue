<template>
  <header>
    <div class="full-logo">
      <div class="full-logo__logo"></div>
      <div class="full-logo__text">
        <span>MOMENTS OF AIR</span>
      </div>
    </div>
    <div class="menu">
      <a href="#" class="menu__item"> Features </a>
      <a class="menu__item" href="#"> Technologies </a>
      <a class="menu__item" href="#"> Who we are </a>
      <a class="menu__item" href="#"> How do we deliver </a>
      <div class="menu__item">
        <button class="primary-button">Buy a set</button>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style lang="scss" scoped>
header {
  position: fixed;
  top: 0;
  left: 0;
  display: flex;
  justify-content: space-around;
  height: 130px;
  width: 100%;
  margin: 0 auto;
  z-index: 2;
}
.full-logo {
  display: flex;
  color: white;
  align-items: center;
  font-family: "Proxima Nova", sans-serif;
  font-size: 18px;
  &__logo {
    height: 46px;
    width: 46px;
    background-image: url(../assets/logo-main.png);
    background-position: center;
    background-repeat: no-repeat;
    margin-right: 20px;
  }
}
.menu {
  display: flex;
  justify-content: space-around;
  align-items: center;
  width: 65%;
  font-size: 14px;
  &__item {
    font-family: "Museo Sans Cyrl", sans-serif;
    color: white;
    font-size: 16px;
    line-height: 28px;
  }
}
</style>
