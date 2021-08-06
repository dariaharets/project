<template>
  <header>
    <div class="full-logo">
      <div class="full-logo__logo"></div>
      <div class="full-logo__text">
        <span>MOMENTS OF AIR</span>
      </div>
    </div>
    <div class="menu">
      <a href="#"
      ><div class="menu__item">
        <p>Features</p>
      </div>
      </a>
      <a href="#">
      <div class="menu__item">
        <p>Technologies</p>
      </div>
      </a>
      <a href="#">
      <div class="menu__item">
        <p>Who we are</p>
      </div>
      </a>
      <a href="#">
      <div class="menu__item">
        <p>How do we deliver</p>
      </div>
      </a>
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
  font-family: 'Proxima Nova', sans-serif;
  font-size: 18px;
  &__logo {
    height: 46px;
    width: 46px;
    background-image: url(../assets/Logo.png);
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
}
</style>
