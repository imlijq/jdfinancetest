<template lang="html">
    <div>
      <Heador></Heador>
      <Slider></Slider>
      <Novice></Novice>
      <Borrow></Borrow>
    </div>
</template>

<script>
import Heador from "../public/header.vue";
import Slider from "./hslider.vue";
import Novice from "./novice.vue";
import Borrow from "./borrow.vue";
export default {
  components: {
    Heador,
    Slider,
    Novice,
    Borrow
  }
};
</script>

<style lang="scss" module>

</style>
