<template>
  <div class="section11">
    <div class="section11__text">
      <h2>Have <strong class="yellow-text">any questions</strong>?</h2>
      <p>Contact us!</p>
      <button class="primary-button">Write</button>
    </div>
    <div class="section11__image"></div>
  </div>
</template>

<script>
export default {
  name: "Section11",
};
</script>

<style  lang="scss" scoped>
.section11 {
  margin: 160px auto;
  height: 450px;
  width: 83%;
  display: flex;
  justify-content: space-between;
  &__text {
    height: 450px;
    width: 350px;
    p {
      padding-top: 40px;
      padding-bottom: 50px;
    }
  }
  &__image {
    width: 641px;
    height: 450px;
    background-image: url("../assets/sect11.png");
    background-repeat: no-repeat;
    background-size: cover;
  }
}
</style>
