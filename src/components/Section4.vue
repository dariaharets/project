<template>
  <div class="section4">
    <div class="section4__image"></div>
    <div class="section4__text">
      <h2>
        <strong class="yellow-text">Lock</strong> and
        <strong class="yellow-text">balance</strong> mounting system
      </h2>
      <p>
        There is no standard for how to attach and balance a lens on a drone, so
        we made one. Introducing our Lock and Balance Mounting System. It’s a
        two part design with a lens on one side and a counterweight on the
        other. The two parts clamp together over the drone’s camera, creating a
        secure lock that doesn’t impede the gimbal.
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: "Section4",
};
</script>

<style  lang="scss" scoped>
.section4 {
  margin: 0 auto;
  height: 355px;
  width: 100%;
  display: flex;
  justify-content: space-around;
  align-items: center;
  &__text {
    height: 355px;
    width: 660px;
    background-image: url("../assets/text-bg-lock.png");
    background-repeat: no-repeat;
  }
  &__image {
    width: 505px;
    height: 355px;
    background-image: url("../assets/lock-bg.png");
    background-repeat: no-repeat;
    background-size: cover;
  }
}
</style>
