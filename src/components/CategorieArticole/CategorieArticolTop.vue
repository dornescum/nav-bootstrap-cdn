<template>
<div>
  <slot>
    <div class="red-background"></div>
    <h2 class="text-center mt-3 mb-3">FENOMENUL POEZIEI CARCERALE</h2>
    <div class="black-background"></div>
  </slot>
</div>
</template>

<script>
export default {
name: "CategorieArticolTop"
}
</script>

<style scoped>

@media screen and (max-width: 768px){
  h2 {
    font-size: 1rem;
  }
}
</style>