<template lang="html">
    <div>
      <Heador></Heador>
      <Slider></Slider>
        <Welfare></Welfare>
        <Service></Service>
      <Footer1></Footer1>
      <Navbar></Navbar>
    </div>
</template>

<script>
import Heador from "../public/header.vue";
import Slider from "./islider.vue";
import Welfare from "./welfare.vue";
import Service from "./service.vue";
import Footer1 from "../public/footer.vue";
import Navbar from "../public/navbar.vue";

export default {
  components: {
    Heador,
    Slider,
    Welfare,
    Service,
    Footer1,
    Navbar,
  }
};
</script>

<style lang="scss">

</style>
