<template>
    <div id="main">
      <Header></Header>
      <TabBar></TabBar>
    </div>
</template>
<script>
import Header from '@/components/Header';
import TabBar from '@/components/TabBar';
export default {
   name:'Movie',
   components:{
     Header,
     TabBar
   }
}
</script>
<style scoped>

</style>
