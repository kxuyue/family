<template>
  <mt-swipe :show-indicators="false">
    <mt-swipe-item class="slide1">13</mt-swipe-item>
    <mt-swipe-item class="slide2">14</mt-swipe-item>
    <mt-swipe-item class="slide3">15</mt-swipe-item>
  </mt-swipe>

</template>
<style>
  .swipe {
    height: 200px;
    color: #fff;
    font-size: 30px;
    text-align: center;
  }

  .swipe-item {
    line-height: 200px;
  }

  .slide1 {
    background-color: #0089dc;
    color: #fff;
  }

  .slide2 {
    background-color: #ffd705;
    color: #000;
  }

  .slide3 {
    background-color: #ff2d4b;
    color: #fff;
  }
</style>
<script>
  export default{
    data(){
      return{
        msg:'hello vue'
      }
    },
    components:{

    }
  }
</script>
