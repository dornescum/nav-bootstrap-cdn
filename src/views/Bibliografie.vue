<template>
<div>
  <BibliografieHead />
  <BibliogarfieMain />
  <BibliogarfiePagination />
</div>

</template>

<script>
import BibliografieHead from "@/components/Bibliografie/BibliografieHead";
import BibliogarfieMain from "@/components/Bibliografie/BibliogarfieMain";
import BibliogarfiePagination from "@/components/Bibliografie/BibliogarfiePagination";
export default {
name: "Bibliografie",
  components:{
    BibliografieHead,
    BibliogarfieMain,
    BibliogarfiePagination
  }
}
</script>

<style scoped>

</style>