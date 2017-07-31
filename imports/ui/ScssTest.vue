<template>
  <div class="scss-test">
    <h1>SCSS Component</h1>
    <div class="colors">
      <span class="red">Red color</span>
      <span class="blue">Blue color</span>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'scss-test'
  }
</script>

<style lang="scss" scoped>

@import '~imports/ui/stylesheets/scss-colors';

$grey-color: grey;

.scss-test {
  color: $grey-color;
}

</style>
