<template>
  <div class="less-test">
    <h1>LESS Component</h1>
    <div class="colors">
      <span class="red">Red color</span>
      <span class="blue">Blue color</span>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'less-test'
  }
</script>

<style lang="less" scoped>

@import '~imports/ui/stylesheets/less-colors';

@grey-color: grey;

.less-test {
  color: @grey-color;
}

</style>
