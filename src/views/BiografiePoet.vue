<template>
  <div>
    <BottomNav />
    <BiografiePoetMain />
  </div>

</template>

<script>
import BiografiePoetMain from "@/components/BiografiePoet/BiografiePoetMain";
import BottomNav from "@/components/Home/BottomNav";
export default {
name: "BiografiePoet",
  components:{
  BiografiePoetMain,
    BottomNav
  }
}
</script>

<style scoped>

</style>