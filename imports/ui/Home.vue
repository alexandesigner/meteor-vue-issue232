<template>
  <div class="home">
    <h1>Welcome Home</h1>
    <p>Create awesome apps with vuejs &amp; meteor! <a href="https://github.com/Akryum/meteor-vue-component">More info</a></p>
    <img src="/img/vue.png" class="logo"/><img src="/img/meteor.png" class="logo"/>
    <less-test></less-test>
    <scss-test></scss-test>
  </div>
</template>

<script>
  import LessTest from '/imports/ui/LessTest.vue'
  import ScssTest from '/imports/ui/ScssTest.vue'
  export default {
    name: 'Home',
    components: {
      LessTest,
      ScssTest
    }
  }
</script>

<style lang="less">

@grey-color: grey;

.home {
  text-align: center;
  color: @grey-color
}

img.logo {
  max-width: 101px;
  margin: 12px;
}

</style>
