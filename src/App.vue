<template>
  <div>
    <Header />
    <Section1 />
    <Section2 />
    <Section3 />
    <Section4 />
    <Section6 />
    <Section7 />    
    <Section8 />
    <Section9 />
    <Section10 />
    <Section11 />
    <Footer />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Section1 from "./components/Section1.vue";
import Section2 from "./components/Section2.vue";
import Section3 from "./components/Section3.vue";
import Section4 from "./components/Section4.vue";
import Section9 from "./components/Section9.vue";
import Section6 from "./components/Section6.vue";
import Section7 from "./components/Section7.vue";
import Section8 from "./components/Section8.vue";
import Section10 from "./components/Section10.vue";
import Section11 from "./components/Section11.vue";
import Footer from "./components/Footer.vue";


export default {
  name: "Home",
  components: {
    Header,
    Section1,
    Section2,
    Section3,
    Section4,
    Section7,
    Section8,
    Section9,
    Section6,
    Section10,
    Section11,
    Footer,
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
@font-face {
  font-family: "Museo Sans Cyrl";
  src: url("/fonts/Museo_Sans_Cyrl_500.ttf") format("truetype");
  font-weight: bold;
  font-style: normal;
}
@font-face {
  font-family: "Proxima Nova";
  src: url("/fonts/Proxima_Nova_Regular.ttf") format("truetype");
  font-weight: bold;
  font-style: normal;
}

body {
  max-width: 1440px;
  width: 100%;
  scroll-behavior: smooth;
  background-color: $dark;
  margin: 0 auto;
  color: white;
}
a {
  text-decoration: none;
  outline: none;
  color: inherit;
  font-style: normal;
}
h1 {
  font-family: "Roboto Condensed", sans-serif;
  font-size: 74px;
  font-weight: bold;
  line-height: 87px;
  margin: 0;
  padding: 0;
}
h2 {
  font-family: "Roboto Condensed", sans-serif;
  font-size: 40px;
  line-height: 54px;
}
h3 {
  font-family: "Roboto Condensed", sans-serif;
  font-size: 22px;
  font-weight: bold;
}
p {
  font-family: "Museo Sans Cyrl", sans-serif;
  font-size: 16px;
  line-height: 28px;
}
.yellow-text {
  color: $yellow;
}
.primary-button {
  width: 160px;
  height: 54px;
  background-color: transparent;
  border-radius: 5px;
  border: 1px solid $yellow;
  color: white;
}
.primary-button:hover {
  background-color: $yellow;
  color: $dark;
}
.secondary-button {
  width: 160px;
  height: 54px;
  background-color: $yellow;
  border-radius: 5px;
  color: $dark;
  border: none;
}
.secondary-button:hover {
  background-color: transparent;
  border: 1px solid $yellow;
  color: white;
}
.wrapper {
  position: relative;
  width: 100%;
}
.price {
  font-size: 20px;
  .decorated {
    text-decoration: line-through;
    color: #afafaf;
    padding-left: 20px;
  }
}
</style>
