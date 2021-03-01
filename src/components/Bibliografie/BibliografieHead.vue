<template>
  <div class="main_container">

   <div class="red_hr"></div>
    <div class="title_cat uppercase semibold center mb20">
      <h6 class="title-main">bibliografie: poezia carcerala </h6>
    </div>
   <div class="small_hr"></div>
    <div>
      <ul class="text-center flex_space-evenly">
        <!--             o rezolv din js-->
        <li class="active"><a href="#" class="active-link">Poezii</a></li>
        <li ><a href="#" class="color-red"> Antologii</a> </li>
        <li ><a href="#" class="color-red"> Critica Literala</a> </li>
      </ul>
    </div>


  </div>
</template>

<script>
export default {
name: "BibliografieHead"
}
</script>

<style scoped>
*{
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}


a {
  color: var(--black-1);
  text-decoration: none;
  font-size: 1rem;
  cursor: pointer;
}

.title-main {
  text-transform: uppercase;
}

.text-center {
  text-align: center;
}
.bold{
  font-weight: bold;
  font-size: 18px;
}
.flex_space-evenly {
  display: flex;
  justify-content: space-evenly;
}

.active-link {
  font-weight: bold;
  color: var(--black-1);
}

.color-red {
  color: var(--red-1);
  font-weight: bold;
}
.red_hr{
  background: var(--red-1);
  margin: 1rem 0;
  height: 0.2rem;
}
.small_hr{
  background: var(--black-1);
  height: 0.1rem;
  margin: 1rem 0;

}

/*.container {*/
/*  width: 100%;*/
/*  margin-right: auto;*/
/*  margin-left: auto;*/
/*}*/

/*.about-book {*/
/*  font-size: 16px;*/
/*  padding: 10px 45px 10px 0;*/
/*  margin: 25px 2px;*/
/*  text-align: left;*/
/*  line-height: var(--lineHeight-1);*/
/*  line-break: auto;*/
/*}*/
/*.img-book{*/
/*  !*margin: 2px 0;*!*/
/*  display: flex;*/
/*  justify-content: center;*/
/*  align-content: center;*/
/*}*/
/*.picture-info {*/
/*  !*width: 100%;*!*/
/*  height: 350px;*/
/*  object-position: center;*/
/*  padding: 15px 5px;*/
/*}*/

/*.row {*/
/*  display: flex;*/
/*  margin-right: -15px;*/
/*  margin-left: -15px;*/
/*  padding: 20px 5px;*/
/*}*/

/*.col-6 {*/
/*  flex: 0 0 50%;*/
/*  max-width: 50%;*/
/*}*/

/*.flex-align {*/
/*  display: flex;*/
/*}*/

/*.book-box {*/
/*  height: 380px;*/
/*  padding: 0 1px;*/
/*  margin: 0;*/
/*}*/

/*@media (max-width: 992px) {*/
/*  .row {*/
/*    display: flex;*/
/*    flex-direction: column;*/
/*    flex-wrap: wrap;*/
/*    padding: 20px 0;*/
/*    margin: auto;*/
/*    width: 100%;*/
/*  }*/

/*  .col-6 {*/
/*    flex: 0 0 50%;*/
/*    max-width: 100%;*/
/*  }*/
/*  .book-info{*/
/*    font-size: 17px;*/
/*  }*/
/*}*/

/*@media (max-width: 768px) {*/
/*  .col-6 {*/
/*    flex: 0 0 50%;*/
/*    max-width: 100%;*/
/*  }*/
/*  .book-info{*/
/*    font-size: 16px;*/
/*  }*/
/*  .about-book{*/
/*    margin: 30px 2px 5px 2px;*/
/*    padding: 10px 2px;*/
/*  }*/

/*  .picture-info{*/
/*    padding: 15px 5px;*/
/*  }*/
/*  .book-box{*/
/*    height: 400px;*/
/*  }*/
/*}*/


/*@media (max-width: 576px) {*/
/*  .row {*/
/*    display: flex;*/
/*    align-items: center;*/
/*    justify-content: center;*/
/*    width: 100%;*/
/*    padding: 10px 15px;*/
/*  }*/
/*  .book-info{*/
/*    font-size: 16px;*/
/*  }*/
/*  .flex-align{*/
/*    flex-direction: column;*/
/*  }*/
/*  .about-book{*/
/*    margin: 10px 2px 5px 2px;*/
/*    padding: 10px 15px;*/
/*  }*/
/*}*/
/*.border-bottom-grey{*/
/*  border: 1px solid var(--grey-1);*/
/*}*/
/*pagination*/
.pagination {
  display: inline-block;
  margin-left: 100px;
}

.pagination a {
  color: black;
  float: left;
  padding: 8px 16px;
  text-decoration: none;
}

.pagination a.active {
  background-color: var(--red-1);
  color: white;
}

.pagination a:hover:not(.active) {background-color: #ddd;}

</style>