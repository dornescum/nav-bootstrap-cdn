<template>
  <div class="mt-6">
    <div class="red-background"></div>
    <div class="">
      <h6 class="title-main m-2"> Videotecă </h6>
    </div>
   <div class="black-background"></div>
    <ul class="text-center display-flex-ct">
      <li class="active"><a href="#" class="active-link color-red links-top">Cantece </a></li>
      <li ><a href="#" class="links-top"> Conferinte</a> </li>
      <li ><a href="#" class="links-top"> Emisiuni </a> </li>
    </ul>
  </div>


</template>

<script>
export default {
name: "VideotecaTop",

}
</script>

<style scoped>
.links-top{
  font-weight: bold;
  font-size: 1.3rem;
  padding: 1rem;
}
.title-main{
  font-size: 2rem;
}
ul li{
  padding: .5rem;
}
a {
  padding: 1rem;
  margin: .5rem;
  font-size: 1rem;
  color: var(--black-1);
  text-decoration: none;
  transition: var(--transition);
}
a:hover{
  color: var(--red-1);
}
.active-link {
  color: var(--red-1);
  text-decoration: none;
}
@media screen and (max-width: 768px){
  .links-top{
    padding: .1rem .3rem;
    font-size: .9rem;
  }
  ul{
    padding: 0;
  }
}
</style>