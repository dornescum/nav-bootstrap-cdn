<template>
  <div>
    <VideotecaTop />
    <VideotecaMain />
  </div>

</template>

<script>
import VideotecaMain from "@/components/Videoteca/VideotecaMain";
import VideotecaTop from "@/components/Videoteca/VideotecaTop";
export default {
name: "Videoteca",
  components:{
  VideotecaMain,
    VideotecaTop
  }
}
</script>

<style scoped>

</style>