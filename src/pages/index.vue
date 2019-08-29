<template>
  <van-button @click='clkbtn'>跳转</van-button>
</template>

<script>
  export default {
    mpType: 'page',

    data() {
      return {}
    },

    components: {},

    methods: {
      clkbtn: function() {
        this.$router.push({
          path: '/packageA/logs',
          query: {
            msg: 'zfw'
          }
        });
      }
    },

    created() {}
  }
</script>

<style scoped>

</style>
