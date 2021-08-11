<template>
  <footer class="footer">
    <div class="footer__logo">
      <div class="footer__logo-logo"></div>
      <div class="footer__logo-text">
        <span>MOMENTS OF AIR</span>
      </div>
    </div>
    <div class="menu">
      <a href="#">
        <div class="menu__item">
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
        <button class="rare-button">Buy a set</button>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style  lang="scss" scoped>
$dark: #171d1f;
$yellow: #fdc400;
$transparent: rgba(246, 246, 246, 0.05);
.footer {
  width: 100%;
  height: 260px;
  background-image: url("../assets/footer.png");
  background-repeat: no-repeat;
  background-size: cover;
  padding-top: 60px;
  color: $dark;
  justify-content: space-around;
  display: flex;
  margin: 0 auto;
  &__logo {
    display: flex;
    justify-content: space-around;
    align-items: center;
    font-family: "Proxima Nova", sans-serif;
    font-size: 18px;
    &-logo {
      height: 47px;
      width: 47px;
      background-image: url("../assets/logo-footer.png");
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
  .rare-button {
    width: 160px;
    height: 54px;
    background-color: transparent;
    border-radius: 5px;
    border: 1px solid $dark;
    color: $dark;
  }
  .rare-button:hover {
    background-color: $yellow;
    color: $dark;
    border: none;
  }
}
</style>
