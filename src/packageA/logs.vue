<template>
  <div>zfw3
  </div>
</template>

<script>

export default {
  components: {
  },

  data () {
    return {
      msg:''
    }
  },
  onLoad() { // query需要在onLoad周期内获取
        let query = this.$route.query;
        console.log('child' + query.msg);
        this.msg = query.msg;
      },
}
</script>

<style>
</style>
