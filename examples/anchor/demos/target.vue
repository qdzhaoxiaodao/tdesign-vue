<template>
  <div class='anchor-demo'>
    <t-anchor-target :id="`${path}#anchor-target-1`">定义</t-anchor-target>
    <t-anchor-target :id="`${path}#anchor-target-2`">服务功能</t-anchor-target>
    <t-anchor-target :id="`${path}#anchor-target-3`">使用指南</t-anchor-target>
    <t-anchor-target :id="`${path}#anchor-target-4`">创建签名</t-anchor-target>
    <t-anchor-target :id="`${path}#anchor-target-5`">创建内容</t-anchor-target>
    <t-anchor-target :id="`${path}#anchor-target-6`">保密协议</t-anchor-target>
    <t-anchor-target :id="`${path}#anchor-target-7`">其他</t-anchor-target>
  </div>
</template>

<script>
export default {
  computed: {
    path() {
      return this?.$route?.path || '';
    },
  },
};
</script>
