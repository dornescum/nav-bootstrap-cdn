<template>
  <div>
    <div class="container">
      <!--        1-->
      <div v-for="book in books" :key="book.id">
        <div class="row">
          <div class="col-lg-6 flex-align book-box">
            <div class="col-lg-6">
              <div class="img-book">
                <img :src="book.foto">
              </div>
            </div>
            <div class="col-lg-6 about-book">
              <p class="book-info"><span class="bold">Titlu :</span><a href="" class="color-red">{{book.title}}</a></p>
              <p class="book-info"><span class="bold">Autor : {{ book.autor }} </span> </p>
              <p class="book-info"><span class="bold">Editura : {{book.editura}}</span> </p>
              <p class="book-info"><span class="bold">Oras : {{ book.orasul }}</span> </p>
              <p class="book-info"><span class="bold">Editia : {{book.editia}} </span> </p>
              <p class="book-info"><span class="bold">Nr. pagini : {{ book.pagini }} </span> </p>
            </div>
          </div>
          <div class="col-lg-6 flex-align book-box">
            <div class="col-lg-6">
              <div class="img-book">
                <img :src="book.foto">
              </div>
            </div>
            <div class="col-lg-6 about-book">
              <p class="book-info"><span class="bold">Titlu :</span><a href="" class="color-red">{{book.title}}</a></p>
              <p class="book-info"><span class="bold">Autor : {{ book.autor }} </span> </p>
              <p class="book-info"><span class="bold">Editura : {{book.editura}}</span> </p>
              <p class="book-info"><span class="bold">Oras : {{ book.orasul }}</span> </p>
              <p class="book-info"><span class="bold">Editia : {{book.editia}} </span> </p>
              <p class="book-info"><span class="bold">Nr. pagini : {{ book.pagini }} </span> </p>
            </div>
          </div>
        </div>
        <div class="border-bottom-grey"></div>
      </div>


    </div>
  </div>

</template>

<script>

export default {
name: "BibliogarfieMain",
  data(){
  return{
    // books: [],
    books: [
      {
        "title": "gigi",
        "autor": "gigi duru",
        "editura": "tei",
        "orasul": "Cluj",
        "editia": "1",
        "pagini": 320,
        "foto": "https://images.unsplash.com/photo-1610386056137-dfb0cc50dca6?ixid=MXwxMjA3fDB8MHx0b3BpYy1mZWVkfDQ1fF84ekZIdWhSaHlvfHxlbnwwfHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60",
        "id": 1
      },
      {
        "title": "gigi1",
        "autor": "gigi duru",
        "editura": "tei",
        "orasul": "Bucuresti",
        "editia": "1",
        "pagini": 320,
        "foto":"https://images.unsplash.com/photo-1491396122992-23bcbe680fe6?ixid=MXwxMjA3fDB8MHxzZWFyY2h8OXx8Y2h1cmNofGVufDB8MXwwfA%3D%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60",
        "id": 2
      },
      {
        "title": "gigi2",
        "autor": "gigi duru",
        "editura": "tei",
        "orasul": "Constanta",
        "editia": "1",
        "pagini": 320,
        "foto": "https://images.unsplash.com/photo-1601293251531-a81cd6add70f?ixid=MXwxMjA3fDB8MHxzZWFyY2h8MTN8fHNwaXJpdHVhbHxlbnwwfDF8MHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60",
        "id":3
      },
      {
        "title": "gigi3",
        "autor": "gigi duru",
        "editura": "tei",
        "orasul": "Timisoara",
        "editia": "1",
        "pagini": 320,
        "foto": "https://images.unsplash.com/photo-1518729582962-98d343ccb9e0?ixid=MXwxMjA3fDB8MHxzZWFyY2h8Mnx8Y3Jpc3RpYW58ZW58MHwxfDB8&ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60",
        "id": 4
      }
    ],
    }
  },
  // mounted(){
  // fetch("http://localhost:3000/books")
  //   .then((response)=>{
  //     response.json()
  //     .then((data)=>{
  //       this.books = data
  //     })
  //     .catch((err)=>{
  //       console.log(err.message)})
  //   })
  // },
  // filters:{
  //   thetown(){
  //    return   this.books.filter((item)=>{
  //      item.orasul === "Bucuresti"
  //    })
  //   }
  // }
}
</script>

<style scoped>
.container {
  width: 100%;
  margin-right: auto;
  margin-left: auto;
}

.about-book {
  font-size: 16px;
  /*padding: 10px 45px 10px 0;*/
  padding: .5rem;
  margin: 2rem 0.3rem;
  text-align: left;
  line-height: var(--lineHeight-1);
  line-break: auto;
}
.book-info{
  margin: .2rem;
  padding: 0.2rem;
}
.img-book{
  /*margin: .2rem;*/
  display: flex;
  justify-content: center;
  align-content: center;
  width: 100%;
  height: 100%;
  object-fit: contain;
}
.picture-info {
  /*width: 100%;*/
  height: 380px;
  object-position: center;
  padding: 15px 5px;
}

.row {
  display: flex;
  margin-right: -15px;
  margin-left: -15px;
  padding: 20px 5px;
}

.col-lg-6 {
  flex: 0 0 50%;
  max-width: 50%;
}

.flex-align {
  display: flex;
}

.book-box {
  height: 380px;
  padding: 0 1px;
  margin: 0;
}
a {
  color: var(--black-1);
  text-decoration: none;
  font-size: 1rem;
  cursor: pointer;
}
.color-red {
  color: var(--red-1);
  font-weight: bold;
}
@media (max-width: 992px) {
  .row {
    display: flex;
    flex-direction: column;
    flex-wrap: wrap;
    padding: 20px 0;
    margin: auto;
    width: 100%;
  }

  .col-lg-6 {
    flex: 0 0 50%;
    max-width: 100%;
  }
  .book-info{
    /*font-size: 17px;*/
  }
}
@media (max-width: 768px) {
  /*.col-6 {*/
  /*  flex: 0 0 50%;*/
  /*  max-width: 100%;*/
  /*}*/
  .book-info{
    padding: .5rem 1rem;
    /*font-size: 16px;*/
  }
  .about-book{
    /*margin: 1rem .2rem .3rem 1.2rem;*/
    margin: 1rem;
    padding: 0.5rem 0.9rem;
  }
    .img-book{
      margin: .1rem;
      padding: 0.2rem;
      height: 20rem;
      width: 20rem;
    }
  .picture-info{
    padding: 0.2rem 0.1rem;
  }
  .book-box{
    height: 400px;
  }
}
@media (max-width: 576px) {
  .row {
    display: flex;
    align-items: center;
    justify-content: center;
    width: 100%;
    padding: .7rem 1rem;
  }
  .book-info{
    /*font-size: 16px;*/
  }
  .flex-align{
    flex-direction: column;
  }
  .about-book{
    margin: 0.3rem 0.1rem 0.1rem 0.1rem;
    padding: 0.6rem 1rem;
  }
  .img-book{
    width: 16rem;
    height: 20rem;
  }
}
@media (max-width: 420px) {
  .about-book{
    margin: 0.3rem;
    padding: 0.3rem;
  }
}
.border-bottom-grey{
  border: 1px solid var(--grey-1);
}
</style>