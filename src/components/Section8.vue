<template>
  <div class="section8">
    <div class="section8__text">
      <h2>Who we are?</h2>
      <p>
        Ready for whatever you can throw at them with advanced hydrophobic
        coatings, scratch resistant glass, and shatterproof construction. From
        Brooklyn to Iceland, these filters are prepared for takeoff wherever you
        feel like flying.
      </p>
      <a href="#">
        <p>
          Learn more
          <i class="fas fa-chevron-circle-right"></i>
        </p>
      </a>
    </div>
    <div class="section8__image"></div>
  </div>
</template>

<script>
export default {
  name: "Section8",
};
</script>

<style  lang="scss" scoped>
.section8 {
  margin: 0 auto;
  height: 400px;
  width: 83%;
  display: flex;
  justify-content: space-between;
  align-items: center;
  &__text {
    height: 350px;
    width: 405px;
    p {
      padding-top: 40px;
    }
  }
  &__image {
    width: 740px;
    height: 400px;
    background-image: url("../assets/sect8.png");
    background-repeat: no-repeat;
    background-size: cover;
  }
}
</style>
