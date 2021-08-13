<template>
  <div class="section10">
    <div class="section10__text">
      <h2>How do we <strong class="yellow-text">deliver</strong>?</h2>
      <a href="#">
        <p>
          Learn more
          <i class="fas fa-chevron-circle-right"></i>
        </p>
      </a>
    </div>
    <div class="section10__image">
      <p>
        Your order is important to us! We make every effort to deliver your
        order in a timely manner. Before you place your order, please read
        through the various delivery options and pick the method that best suits
        your needs. Questions? Send us a quick email to orders@bdel.com and
        we'll get you an answer promptly.
        <br />
        <br />
        Most orders are shipped the next business day after we receive your
        order.
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: "Section10",
};
</script>

<style  lang="scss" scoped>
.section10 {
  margin: 0 auto;
  height: 225px;
  width: 83%;
  display: flex;
  justify-content: space-between;
  align-items: center;
  &__text {
    height: 220px;
    width: 350px;
    background-image: url("../assets/how.png");
    background-repeat: no-repeat;
  }
  &__image {
    width: 641px;
    height: 220px;
  }
}
</style>
