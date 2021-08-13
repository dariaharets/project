<template>
  <div class="section9">
    <div class="section9__image"></div>
    <div class="section9__text">
      <h2>
        Just make <strong class="yellow-text">one click</strong>
        and we will send you our set!
      </h2>
      <p class="price">
        200 USD
        <span class="decorated">270 USD</span>
      </p>
      <button class="secondary-button">Buy</button>
    </div>
  </div>
  <div class="questions"></div>
</template>

<script>
export default {
  name: "Section9",
};
</script>

<style  lang="scss" scoped>
.section9 {
  margin: 0 auto;
  height: 580px;
  width: 85%;
  display: flex;
  justify-content: space-around;
  align-items: center;
  &__text {
    height: 355px;
    width: 503px;
    p {
      padding-top: 40px;
      padding-bottom: 50px;
    }
  }
  &__image {
    width: 560px;
    height: 363px;
    background-image: url("../assets/sect9.png");
    background-repeat: no-repeat;
    background-size: cover;
  }
}
.questions {
  width: 83%;
  height: 73px;
  background-image: url("../assets/questions.png");
  background-repeat: no-repeat;
  margin: 0 auto;
}
</style>
