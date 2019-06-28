<template>
  <div class="homeWrap">
    <el-image :src="homePic" class="bannerPic"></el-image>
  </div>
</template>
<script>
export default {
  name: 'home',
  data () {
    return {
      homePic: require('@/assets/images/1.jpg')
    }
  }
}
</script>
<style lang="less">
  .homeWrap {
    .bannerPic {
    }
  }
</style>
