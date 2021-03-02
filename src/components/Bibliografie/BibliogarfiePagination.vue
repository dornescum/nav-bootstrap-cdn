<template>
  <div class="pagination m-2">
    <a href="#">&laquo;</a>
    <a href="#">1</a>
    <a class="active" href="#">2</a>
    <a href="#">3</a>
    <a href="#">4</a>
    <a href="#">5</a>
    <a href="#">6</a>
    <a href="#">&raquo;</a>
  </div>
</template>

<script>
export default {
name: "BibliogarfiePagination"
}
</script>

<style scoped>
/*pagination*/
.pagination {
  display: inline-block;
  margin-left: 100px;
}

.pagination a {
  color: black;
  float: left;
  padding: 0.5rem 1rem;
  text-decoration: none;
}

.pagination a.active {
  background-color: var(--red-1);
  color: white;
}

.pagination a:hover:not(.active) {background-color: #ddd;}
@media (max-width: 992px){
  .pagination a{
    padding: 0.5rem 0.7rem;
  }
}
</style>