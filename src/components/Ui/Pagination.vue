<template>
  <div class="m-1 display-flex-ct">
    <div class="pagination">
      <a href="#">&laquo;</a>
      <a href="#">1</a>
      <a class="active" href="#">2</a>
      <a href="#">3</a>
      <a href="#">4</a>
      <a href="#">5</a>
      <a href="#">6</a>
      <a href="#">&raquo;</a>
    </div>
  </div>
</template>

<script>
export default {
name: "Pagination"
}
</script>

<style scoped>
.pagination {
  display: flex;
  justify-content: center;
  align-content: center;
}

.pagination a {
  color: black;
  float: left;
  padding: 8px 16px;
  text-decoration: none;
  transition: var(--transition);
}

.pagination a.active {
  background-color: var(--red-1);
  color: white;
}

.pagination a:hover:not(.active) {background-color: #ddd;}

</style>