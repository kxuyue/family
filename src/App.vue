<template>
  <div id="app">
    <!--<mt-header title="首页">
      <mt-button v-link="'/'" icon="back" slot="left">返回</mt-button>
      <mt-button icon="more" slot="right"></mt-button>
    </mt-header>-->
    <!-- main view -->
    <router-view
      class="view"
      keep-alive
      transition
      transition-mode="out-in">
    </router-view>
  </div>

</template>

<script>
  // import Hello from './components/Hello'

  // export default {
  //   components: {
  //     Hello
  //   }
  // }
</script>

<style>
</style>
