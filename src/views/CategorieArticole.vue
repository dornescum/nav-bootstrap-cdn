<template>
<div>
  <BottomNav />
  <CategorieArticolTop/>
  <CategorieArticoleMaine />
</div>
</template>

<script>
import BottomNav from "@/components/Home/BottomNav";
import CategorieArticolTop from "@/components/CategorieArticole/CategorieArticolTop";
import CategorieArticoleMaine from "@/components/CategorieArticole/CategorieArticoleMaine";
export default {
name: "CategorieArticole",
  components:{
  CategorieArticolTop,
    BottomNav,
    CategorieArticoleMaine
  }
}
</script>

<style scoped>

</style>