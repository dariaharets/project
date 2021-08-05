<template>
  <div>
    <Header />
    <Section1 />
    <Section2 />
    <Section3 />
    <Section4 />
  </div>
</template>

<script>
import Header from "../components/Header.vue";
import Section1 from "../components/Section1.vue";
import Section2 from "../components/Section2.vue";
import Section3 from "../components/Section3.vue";
import Section4 from "../components/Section4.vue";

export default {
  name: "Home",
  components: {
    Header,
    Section1,
    Section2,
    Section3,
    Section4,
  },
};
</script>

<style lang="scss">
$dark: #171d1f;
$yellow: #fdc400;
$transparent: rgba(246, 246, 246, 0.05);
@font-face {
  font-family: "Museo Sans Cyrl";
  src: url("/fonts/Museo_Sans_Cyrl_300.ttf") format("truetype");
  font-weight: normal;
  font-style: normal;
}
@font-face{
    font-family: 'Museo Sans Cyrl';
    src: url('/fonts/Museo_Sans_Cyrl_500.ttf') format('truetype');
    font-weight: bold;
    font-style: normal;
}
@font-face{
    font-family: 'Proxima Nova';
    src: url('/fonts/Proxima_Nova_Regular.ttf') format('truetype');
    font-weight: bold;
    font-style: normal;
}

body {
  max-width: 1440px;
  width: 100%;
  scroll-behavior: smooth;
  background-color: black;
}

h1 {
  font-family: "Roboto Condensed", sans-serif;
  font-size: 74px;
  font-weight: bold;
  line-height: 87px;
  color: white;
}
h2 {
  font-family: "Roboto Condensed", sans-serif;
  font-size: 40px;
  line-height: 54px;
  color: white;
}
p {
  font-family: "Museo Sans Cyrl", sans-serif;
  color: white;
  font-size: 16px;
  line-height: 28px;
}
button {
  width: 160px;
  height: 54px;
  background-color: transparent;
  border-radius: 5px;
  border: 1px solid $yellow;
  color: white;
}
button:hover {
  background-color: $yellow;
  color: $dark;
}
.wrapper {
  position: relative;
  width: 100%;
}
</style>
