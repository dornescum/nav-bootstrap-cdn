<template>
<div class="custom-author">

    <h4 class="title">Nichifor Crainic</h4>

<div class="links">
  <a href="javascript:;" class="author-links">Poezii</a>
  <a href="javascript:;" class="author-links">Sinteza operei</a>
</div>





</div>
</template>

<script>
export default {
name: "BiografieTop"
}
</script>

<style scoped>
.custom-author{
  display:flex;
  justify-content: space-between;
}
.title{
  padding: .5rem .5rem .5rem 0;
  margin:.5rem .5rem .5rem 0.1rem;
  color: var(--red-1);
}
.links {
  display: flex;
  justify-content: center;
  align-content: center;
}
.author-links{
  color: var(--black-1);
  background: var(--grey-3);
  border: 2px solid transparent;
  font-size: 1rem;
  max-width: 12rem;
  padding: .2rem .5rem;
  text-align: center;
  transition: 0.5s;
  width: 9rem;
  margin: .8rem;
  text-decoration: none;
  outline: none;
  box-shadow: var(--light-shadow);
}
.author-links:hover{
  background: var(--white);
  box-shadow: var(--dark-shadow);
}
@media screen and (max-width: 768px){

  .title{
    text-align: start;
  }
  .author-links{
    margin: 0;
    padding: 0;
  }
}
@media screen and (max-width: 567px){
  .custom-author{
    flex-direction: column;
  }
  .title{
    text-align:center;
  }
  .author-links{
    margin: 0.1rem;
    padding: 0.1rem;
  }
}
</style>