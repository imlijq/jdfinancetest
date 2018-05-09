<template lang="html">
    <div>
      <Heador></Heador>
      <Slider></Slider>
        <Daily></Daily>
        <In></In>
        <More></More>
      <Footer1 cname="mfooter"></Footer1>
      <Navbar></Navbar>
    </div>
</template>

<script>
import Heador from "../public/header.vue";
import Slider from "./rslider.vue";
  import Daily from "./daily.vue";
  import In from "./in.vue";
  import More from "./more.vue";
import Footer1 from "../public/footer.vue";
import Navbar from "../public/navbar.vue";

export default {
  components: {
    Heador,
    Slider,
      Daily,
      In,
      More,
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
