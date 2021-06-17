<template>
  <div id="tab-bar">
    <slot></slot>
  </div>
</template>

<script>
export default {
  name: "tabbar"
}
</script>

<style scoped>

#tab-bar{

  display: flex;
  position: fixed;
  bottom: 0;
  left: 0;
  right: 0;
  background-color:#f6f6f6;
  box-shadow: 0px -1px 7px rgba(100 ,100, 100, .2);
}
</style>
