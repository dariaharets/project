<template>
  <div class="section2">
    <div class="section2__image">
      <div class="secton2__image-logo"></div>
    </div>
    <div class="section2__text">
      <h2>
        Essential <span class="yellow-text">blogger</span> accessories and
        <span class="yellow-text">filmmaker’s</span> tool
      </h2>
      <p>
        We put our prototypes in the hands of our favorite drone flyers and
        filmmakers. What they captured in a few days blew our minds. We can't
        wait to see what you capture with this gear.
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: "Section2",
};
</script>

<style  lang="scss" scoped>
.section2 {
  height: 650px;
  width: 100%;
  display: flex;
  justify-content: space-around;
  align-items: center;
  &__text {
    height: 255px;
    width: 660px;
    background-image: url(../assets/text-bg.png);
    background-repeat: no-repeat;
  }
  &__image {
    width: 505px;
    height: 355px;
    background-image: url(../assets/guy.png);
    background-repeat: no-repeat;
    background-size: cover;
    position: relative;
    .secton2__image-logo {
      width: 70px;
      height: 70px;
      background-image: url(../assets/logo-2.png);
      background-repeat: no-repeat;
      background-position: center;
      position: absolute;
      top: -15px;
      right: -15px;
    }
  }
}
</style>
