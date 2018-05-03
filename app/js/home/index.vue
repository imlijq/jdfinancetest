<template lang="html">
    <div>
      <Heador></Heador>
      <Slider></Slider>
      <Novice></Novice>
      <Borrow></Borrow>
      <Money></Money>
      <Product></Product>
    </div>
</template>

<script>
import Heador from "../public/header.vue";
import Slider from "./hslider.vue";
import Novice from "./novice.vue";
import Borrow from "./borrow.vue";
import Money from "./money.vue";
import Product from "./product.vue";
export default {
  components: {
    Heador,
    Slider,
    Novice,
    Borrow,
    Money,
    Product,
  }
};
</script>

<style lang="scss" module>

</style>
