<template lang="html">
    <div>
        <Heador/>
        <Slider/>
        <Welfare/>
        <Service/> 
        <Footor />  
        <Navbar/>      
             
    </div>
</template>

<script>
import Heador from "../public/header.vue";
import Footor from "../public/footer.vue";
import Navbar from "../public/navbar.vue";
import Slider from "./islider.vue";
import Welfare from "./welfare.vue";
import Service from "./service.vue";

export default {
  components: {
    Heador,
    Slider,
    Footor,
    Navbar,
    Welfare,
    Service,
  },
  data() {
    return {};
  },

  created() {},

  methods: {}
};
</script>

<style lang="scss" >

</style>
