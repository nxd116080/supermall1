<!-- 下面导航的组件 -->
<template>
  <div>
    <div id="tab-bar">
      <slot></slot>  
    </div>
  </div>
</template>

<script>
export default {
  name:'TabBar',
  data() {
    return {};
  },
  //生命周期 - 创建完成（访问当前this实例）
  created() {},
  //生命周期 - 挂载完成（访问DOM元素）
  mounted() {}
};
</script>
<style scoped>
#tab-bar {
  display: flex;
  background-color: #f6f6f6;

  position: fixed;
  left: 0;
  right: 0;
  bottom: 0;

  box-shadow: 0px -1px 1px rgba(100, 100, 100, 0.2);
}

</style>