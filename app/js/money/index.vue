<template lang="html">
    <div>
      <Heador></Heador>
      <Slider></Slider>
        <Ada></Ada>
        <Money></Money>
        <Adb></Adb>
        <Finance></Finance>
        <Adc></Adc>
      <Footer1 cname="mfooter"></Footer1>
      <Navbar></Navbar>
    </div>
</template>

<script>
import Heador from "../public/header.vue";
import Slider from "./mslider.vue";
import Ada from "./ada.vue";
import Money from "./money.vue";
import Adb from "./adb.vue";
import Finance from "./finance.vue";
import Adc from "./adc.vue";
import Footer1 from "../public/footer.vue";
import Navbar from "../public/navbar.vue";

export default {
  components: {
    Heador,
    Slider,
    Ada,
    Money,
    Adb,
    Finance,
    Adc,
    Footer1,
    Navbar,
  }
};
</script>

<style lang="scss">
  .mfooter{
    margin-top: 0 !important;
    ul{
      li:first-child{
        display: none;
      }
    }
  }
</style>
