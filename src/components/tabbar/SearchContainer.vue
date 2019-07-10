<template>
  <div>
    <h3>SearchContainer</h3>
  </div>
</template>

<script>
import { Toast } from 'mint-ui';

  export default {
    created() {
      Toast({
        message: '请求服务器失败',
        position: 'bottom',
        duration: 5000
      });
    }
  }
</script>

<style lang="scss" scoped>

</style>
