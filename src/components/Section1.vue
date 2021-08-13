<template>
  <div id="#section1" class="section1">
    <h1>Essential lens, filters, and cases for drones</h1>
    <div class="section1__buttons">
      <button class="secondary-button">Buy a set</button>
      <a href="#">
        <p>
          How do we deliver?
          <i class="fas fa-chevron-circle-right"></i>
        </p>
      </a>
    </div>
    <a href="#section2"><div class="scroll"></div></a>
  </div>
</template>

<script>
export default {
  name: "Section1",
};
</script>

<style  lang="scss" scoped>
.section1 {
  width: 100%;
  height: 776px;
  background-image: url(../assets/bg1.png);
  background-repeat: no-repeat;
  background-size: cover;
  margin: 0 auto;
  position: relative;
  &__buttons {
    height: 54px;
    width: 445px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding-left: 100px;
    padding-top: 20px;
  }
  h1 {
    width: 760px;
    height: 175px;
    padding-top: 405px;
    padding-left: 100px;
  }
  .scroll {
    position: absolute;
    height: 100px;
    width: 100px;
    background-image: url(../assets/scroll.png);
    background-repeat: no-repeat;
    background-position: center;
    right: 0;
    top: 640px;
  }
}
</style>
