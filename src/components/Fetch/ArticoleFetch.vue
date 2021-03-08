<template>
  <div class="container">
    <!--    1-->
    <div  v-for="articol in articole" :key="articol.id">
      <div class="row box-article" >
        <div class="col-lg-7">
          <h2 class="title-h2 pt-1">{{articol.title}}</h2>
          <p class="text-para">{{articol.desc}}</p>
          <div class="info-link">
            <a :href="articol.link">citeste mai departe
              <i class="fa fa-angle-double-right info-icon" aria-hidden="true"></i>
            </a>
          </div>
        </div>
        <div class="col-lg-5">
          <div class="img-book">
            <img :src="articol.img" alt="books" class="picture-info">
          </div>
        </div>
      </div>
    </div>



<!--    <div class="row text-articol box-article">-->
<!--      <h2 class="title-h2 pl-2 pt-1">In ce conditii s-a nascut poedia din inchisori</h2>-->
<!--      <p class="text-para p-2">Lorem ipsum dolor sit amet, consectetur adipisicing elit.A dolore, eos incidunt magni officiis praesentium quasi ratione repellat voluptate voluptates! A autem debitis excepturi porro ratione repellat tempore voluptatem. Aspernatur! Lorem ipsum dolor sit amet, consectetur adipisicing elit. Corporis eaque esse in ratione, repellat saepe? Ad alias aperiam consectetur deleniti, dolores, dolorum eos eveniet id in inventore ipsa ipsum labore, magnam odio porro quidem recusandae rem repudiandae tempora vitae. A distinctio facilis in molestiae mollitia qui quidem repellendus sapiente voluptatibus? Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>-->
<!--      <div class="info-link">-->
<!--        <a href="#" class="p-2">citeste mai departe-->
<!--          <i class="fa fa-angle-double-right info-icon" aria-hidden="true"></i>-->
<!--        </a>-->
<!--      </div>-->
<!--    </div>-->
  </div>
</template>

<script>
export default {
name: "ArticoleFetch",
  data(){
  return{
    articole: [
      {
        title: "ceva",
        desc:"Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.",
        img: "https://images.unsplash.com/photo-1499209974431-9dddcece7f88?ixid=MXwxMjA3fDB8MHxzZWFyY2h8MjB8fHByYXl8ZW58MHx8MHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60",
        id:"1",
        link:"./"
      },
          {
        title: "ceva 1",
        desc:"Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.",
        img: "https://images.unsplash.com/photo-1499209974431-9dddcece7f88?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80",
        id:"2",
            link:"./"
          },
          {
        title: "ceva 2",
        desc:"Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.",
        img: "https://images.unsplash.com/photo-1490730141103-6cac27aaab94?ixlib=rb-1.2.1&ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&auto=format&fit=crop&w=1050&q=80",
        id:"3",
            link:"./"
          },
          {
        title: "ceva 3",
        desc:"Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.",
        img: "https://images.unsplash.com/photo-1534629938736-b1b076531d3b?ixlib=rb-1.2.1&ixid=MXwxMjA3fDB8MHxjb2xsZWN0aW9uLXBhZ2V8MnwxMTQyOTIwOHx8ZW58MHx8fA%3D%3D&auto=format&fit=crop&w=500&q=60",
        id:"4",
            link:"./"
          },
          {
        title: "ceva 4",
        desc:"Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.",
        img: "https://images.unsplash.com/reserve/YEc7WB6ASDydBTw6GDlF_antalya-beach-lulu.jpg?ixlib=rb-1.2.1&ixid=MXwxMjA3fDB8MHxjb2xsZWN0aW9uLXBhZ2V8MTZ8MTE0MjkyMDh8fGVufDB8fHw%3D&auto=format&fit=crop&w=500&q=60",
        id:"5",
            link:"./"
          },
          {
        title: "ceva 5",
        desc:"Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.",
        img: "https://images.unsplash.com/photo-1543357480-c60d40007a3f?ixid=MXwxMjA3fDB8MHxjb2xsZWN0aW9uLXBhZ2V8MTJ8ODI4MjU1Njh8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60",
        id:"6",
            link:"./"
          },

    ]
  }
  },
  // mounted(){
  // // fetch("data/articole.json")
  // //   .then((response)=>{
  // //     response.json()
  // //     .then((data)=>{
  // //       this.books = data
  // //     })
  // //     .catch((err)=>{
  // //       console.log(err)})
  // //   })
  //
  //
  //
  //   fetch('https://jsonplaceholder.typicode.com/todos/1')
  //       .then(response => response.json())
  //       .then(data => this.articole =data)
  //       .catch((err) =>{
  //         console.log(err.message)})
  // }

}
</script>

<style scoped>
.box-article{
  margin: 1rem 0;
}
.title-h2{
  color: var(--red-1);
}
.text-para{
  font-size: 1rem;
  color: var(--font-grey);
  letter-spacing: var(--line-spacing);
  text-align: start;
}
/*.grey-background{*/
/*  background-color: var(--grey-2);*/
/*}*/
.info-icon{
  font-size: 0.8rem !important;
  color: var(--red-1);
  padding: 0;
}
.info-link{
  font-size: 1rem;
  display: flex;
  padding: 0 0 0 1rem;
}
.info-link a{
  text-decoration: none;
  color: var(--black-1);
  text-align: start;
}
.text-articol{
  padding:  1rem 0;
}
.picture-info {
  width: 100%;
  height: 22rem;
  object-position: center;
  padding: 1rem .4rem;
  cursor: pointer;
}
.img-book{
  /*margin: 2px 0;*/
  display: flex;
  justify-content: center;
  align-content: center;
}
@media (max-width: 992px){
  .row{
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    align-items: center;
    justify-content: center;
  }
  .picture-info{
    height: 28rem;
    object-position: center;
    padding: 15px 5px;
  }

  .info-link{
    font-size: 0.8rem;
  }
}
@media (max-width: 768px){
  .picture-info{
    height: 28rem;
    object-position: center;
    padding: 15px 5px;
  }
}
@media (max-width: 576px){
  .row {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    width: 100%;
    padding: 1px 5px;
  }
  .text-para{
    padding: 5px !important;
    font-size: 0.7rem;
  }

  .title-h2{
    padding: 1px 0 5px 5px !important;
    font-size: 1rem;
  }
  .info-link{
    font-size: 0.7rem;
  }
  a {
    padding: 0.3rem !important;
  }
  .text-articol{
    padding: 2rem;
  }
  .picture-info{
    height: 16rem;
    object-position: center;
    padding: 15px 5px;
    width: 100%;

  }
}
</style>