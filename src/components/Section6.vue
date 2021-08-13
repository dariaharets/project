<template>
  <div class="section6">
    <div class="section6__text">
      <h2>Cinema <strong class="yellow-text">Glass</strong></h2>
      <p>
        Backed by our heritage of award winning lenses, we brought our cinematic
        glass to drones. Combined with our proprietary coatings, these filters
        deliver the smoothest, crispiest, color neutral image imaginable.
      </p>
    </div>
    <div class="section6__image"></div>
  </div>
</template>

<script>
export default {
  name: "Section6",
};
</script>

<style  lang="scss" scoped>
.section6 {
  margin: 0 auto;
  height: 580px;
  width: 85%;
  display: flex;
  justify-content: space-around;
  align-items: center;
  &__text {
    height: 355px;
    width: 503px;
    background-image: url("../assets/cinema-bg.png");
    background-repeat: no-repeat;
  }
  &__image {
    width: 505px;
    height: 355px;
    background-image: url("../assets/sect6.png");
    background-repeat: no-repeat;
    background-size: cover;
  }
}
</style>