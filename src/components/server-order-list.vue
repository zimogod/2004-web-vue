<template>
  <div class="server-order-list">
      我是服务单列表：{{ msg }}----{{ list }}
  </div>
</template>

<script>
export default {
  name: 'server-order-list',
//   data是命名变量，存放数据的
  data(){
    return {
        msg:'我是你们的剑哥哥'
    }
  },
  props:{
      list:{
          type:Array,
          default:() => []
      }
  }
}
</script>

<style lang="less" scoped>
    .server-order-list{
        width: 100%;
        height: 400px;
        background:gold;
    }
</style>