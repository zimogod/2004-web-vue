<template>
  <div class="home">
    home---
    <server-order-list :list="list" />
  </div>
</template>

<script>
import serverOrderList from '../components/server-order-list';
export default {
  name: 'Home',
  // 注册组件
  components:{
    serverOrderList
  },
  data(){
    return {
        list:[3,4,5,6]
    }
  }
}
</script>
