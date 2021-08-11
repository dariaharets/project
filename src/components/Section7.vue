<template>
  <div class="section7">
    <div class="section7__image"></div>
    <div class="section7__text">
      <h2>Shatterproof Construction</h2>
      <p>
        Ready for whatever you can throw at them with advanced hydrophobic
        coatings, scratch resistant glass, and shatterproof construction. From
        Brooklyn to Iceland, these filters are prepared for takeoff wherever you
        feel like flying.
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: "Section7",
};
</script>

<style  lang="scss" scoped>
.section7 {
  margin: 0 auto;
  height: 680px;
  width: 83%;
  display: flex;
  justify-content: space-between;
  align-items: center;
  &__text {
    height: 235px;
    width: 550px;
    background-image: url("../assets/shatter-bg.png");
    background-repeat: no-repeat;
  }
  &__image {
    width: 460px;
    height: 680px;
    background-image: url("../assets/sect7.png");
    background-repeat: no-repeat;
    background-size: contain;
  }
}
</style>