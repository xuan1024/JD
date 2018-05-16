<template>
  <div>
      <button class="demo" @click="demoClick">click me</button>
  </div>
</template>

<script>
    export default {
        name: 'demoTemp',
        props: ['params'],
        data () {
            return {
                self: this,
                res: '',
            }
        },
        created () {
            
        },
        methods :{
            demoClick () {
                this.res = this.params + 1;
                // this.$eventHub.$emit("getP", this.res);
                this.$emit("getP", this.res);
            }         
        },


        
    }
</script>

<style lang="scss">
    .demo{
        margin-top: 200px;
        color: red;
    }

</style>

