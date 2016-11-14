<style>
  *{
    margin: 0;
    padding: 0;
    font-family:"微软雅黑";
  }
  body{
    background: url(assets/images/backgroud.jpg);
  }
</style>
<template>
  <div v-show="state">
    <router-view></router-view>
  </div>

</template>
<script>
  var data = {
    state:false
  }
  export default {
    data: function(){
      return data;
    }
  }

</script>
