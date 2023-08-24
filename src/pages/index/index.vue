<script setup lang="ts">
import { onLoad } from '@dcloudio/uni-app';
import { ref } from 'vue';
const name = ref('jack');
const onChange: UniHelper.ScrollViewOnScroll = (e) => {
  console.log(e.detail);
};
onLoad(() => {
  console.log(name.value);
});
</script>
<template>
  <view class="test">
    <view>测试</view>
    <uni-badge text="1"></uni-badge>
  </view>
</template>
<style lang="scss"></style>
