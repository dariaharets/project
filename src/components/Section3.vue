<template>
        <div class="section3">
            <div class="section3__text">
                <h2>Buy a set with a <strong class="yellow-text">30%</strong> discount</h2>
                <p>These baby filters make your drone look faster. Or at least you won’t lose them like those other
                    black filters</p>
            </div>
            <div class="section3__slider">
                <div class="section3__slider-slide">
                    <img class="section3__slider-image" alt="sorry" src="../assets/slide1.png"/>
                    <h3>Fire engine red filters set</h3>
                    <p>These baby filters make your drone look faster. Or at least you won’t
                        lose them like those other black filters</p>
                        <p class="price">240 USD
                        <span class="decorated">260 USD</span>
                        </p>
                    <button class="primary-button slide-button">Buy</button>
                </div>
                <div class="section3__slider-slide">
                    <img class="section3__slider-image" alt="sorry" src="../assets/slide2.png"/>
                    <h3>Attach ND filters</h3>
                    <p>Not only do these filters work seamlessly with the camera mounts on both Mavic 2 Drones...</p>
                        <p class="price">370 USD</p>
                    <button class="primary-button slide-button">Buy</button>
                </div>
                <div class="section3__slider-slide">
                    <img class="section3__slider-image" alt="sorry" src="../assets/slide3.png"/>
                    <h3>Drone landing pad</h3>
                    <p>The helipad that does more for you. Like a changing mat for your surf session, the landing pad acts as...</p>
                        <p class="price">228 USD
                        </p>
                    <button class="primary-button slide-button">Buy</button>
                </div>
                <div class="section3__slider-slide">
                    <img class="section3__slider-image" alt="sorry" src="../assets/slide4.png"/>
                    <h3>Ultra thin photo case</h3>
                    <p>Inspired by filmmakers, drone flyers, and minimalists this is the case you don’t have to take off to use.</p>
                        <p class="price">183 USD
                        <span class="decorated">210 USD</span>
                        </p>
                    <button class="primary-button slide-button">Buy</button>
                </div>
            </div>
        </div>
</template>

<script>
export default {
  name: "Section3",
};
</script>

<style  lang="scss" scoped>
.section3 {
  width: 100%;
  height: 895px;
  &__text {
    width: 595px;
    padding-left: 100px;
  }
  &__slider {
    width: 90%;
    height: 570px;
    display: flex;
    justify-content: space-around;
    margin: 70px auto;
    &-slide {
      height: 565px;
      width: 275px;
      .section3__slider-image {
        width: 100%;
        height: 200px;
      }
      .slide-button {
        width: 272px;
        text-align: center;
      }
      .price {
        font-size: 20px;
        .decorated {
          text-decoration: line-through;
          color: #afafaf;
          padding-left: 20px;
        }
      }
    }
  }
}
</style>
