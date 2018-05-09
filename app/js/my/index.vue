<template lang="html">
    <div>
      <Heador></Heador>
      <Slider></Slider>
      <Novice></Novice>
      <Borrow></Borrow>
      <Money></Money>
      <Product></Product>
      <Life></Life>
      <Footer1></Footer1>
      <Navbar></Navbar>
    </div>
</template>

<script>
import Heador from "../public/header.vue";
import Slider from "./hslider.vue";
import Novice from "./novice.vue";
import Borrow from "./borrow.vue";
import Money from "./money.vue";
import Product from "./product.vue";
import Life from "./life.vue";
import Footer1 from "../public/footer.vue";
import Navbar from "../public/navbar.vue";

export default {
  components: {
    Heador,
    Slider,
    Novice,
    Borrow,
    Money,
    Product,
    Life,
    Footer1,
    Navbar,
  }
};
</script>

<style lang="scss" module>

</style>
