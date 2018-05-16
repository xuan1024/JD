<template lang="html">
    <div>
        <Heador/>
        <Slider />
        <Ada/>  
        <Money/> 
        <Adb/>  
        <Finace/>  
        <adc/>  
        <Footor cname="mfooter"/>  
        <Navbar/>  
      
       
    </div>
</template>

<script>
import Heador from "../public/header.vue";
import Footor from "../public/footer.vue";
import Navbar from "../public/navbar.vue";
import Slider from "./mslider.vue";
import Ada from "./ada.vue";
import Money from "./money.vue";
import Adb from "./adb.vue";
import Finace from "./finace.vue";
import adc from "./adc.vue";

export default {
  components: {
    Heador,
    Slider,
    Ada,
    Money,
    Adb,
    Finace,
    adc,
    Footor,
    Navbar
  },
  data() {
    return {};
  },

  created() {},

  methods: {}
};
</script>

<style lang="scss" >
.mfooter{
  ul{
    li:first-child{
      display: none;
    }
  }
}
</style>
