<template>

    <div class="container" >
<!--      <div v-if="loading">Loading ...</div>-->
      <!--        1-->
      <div class="row-flex-wrap">
        <div class="columns" v-for="video in videos" :key="video.id">
          <div class="border">
            <div class="video-container">
              <iframe width="300" height="240" :src="video.videoLink" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen class="video-link"></iframe>
            </div>

            <div class="foto-link display-flex-sb-main">
              <img src="https://images.unsplash.com/photo-1614185538813-dbcebdc3ecfa?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80" alt="" class="foto-link-img">
              <p class="video-para">{{video.title}}</p>
            </div>
            <div class="video-about">
              <p class="bold">Versuri :<span class="video-title"> {{video.lyrics}}</span></p>
              <p  class="bold">Muzica/voce :<span class="video-music"> {{video.music}}</span></p>
            </div>

          </div>
        </div>



      </div>

      <Pagination />
    </div>


</template>

<script>
import Pagination from "@/components/Ui/Pagination";
export default {
name: "VideotecaMain",
  components:{
  Pagination
  },
  data(){
    return{
      loading: false,
      videos:[
        {
          title:"Colindul robului 1",
          avatar:"https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQcbNVB6ZofywgxyNHqU6jjpJTX-URIUGuQwg&usqp=CAU",
          lyrics:"Valeriu Gafencu",
          music:"Dan Vasilescu(Trupa Acum)",
          videoLink: "https://www.youtube.com/embed/hF9Gr5waAJg",
          id: 1
        },
        {
          title:"Colindul robului 1",
          avatar:"https://youtu.be/F10IetLz71s",
          lyrics:"Valeriu Gafencu",
          music:"Dan Vasilescu(Trupa Acum)",
          videoLink: "https://www.youtube.com/embed/F10IetLz71s",
          id: 2
        },
  {
          title:"Colindul robului 1",
          avatar:"https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQcbNVB6ZofywgxyNHqU6jjpJTX-URIUGuQwg&usqp=CAU",
          lyrics:"Valeriu Gafencu",
          music:"Dan Vasilescu(Trupa Acum)",
          videoLink: "https://www.youtube.com/embed/U7r2YwvBgQ0",
          id: 3
        },
        {
          title:"Colindul robului 1",
          avatar:"https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQcbNVB6ZofywgxyNHqU6jjpJTX-URIUGuQwg&usqp=CAU",
          lyrics:"Valeriu Gafencu",
          music:"Dan Vasilescu(Trupa Acum)",
          videoLink: "https://www.youtube.com/embed/-AJrAem0YyA",
          id: 4
        },
 {
          title:"Colindul robului 1",
          avatar:"https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQcbNVB6ZofywgxyNHqU6jjpJTX-URIUGuQwg&usqp=CAU",
          lyrics:"Valeriu Gafencu",
          music:"Dan Vasilescu(Trupa Acum)",
          videoLink: "https://www.youtube.com/embed/LJ7qXHjxj_0",
          id:5
        },
 {
          title:"Colindul robului 1",
          avatar:"https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQcbNVB6ZofywgxyNHqU6jjpJTX-URIUGuQwg&usqp=CAU",
          lyrics:"Valeriu Gafencu",
          music:"Dan Vasilescu(Trupa Acum)",
          videoLink: "https://www.youtube.com/embed/KhaUnHJjS8A",
          id:6
        },
 {
          title:"Colindul robului 1",
          avatar:"https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQcbNVB6ZofywgxyNHqU6jjpJTX-URIUGuQwg&usqp=CAU",
          lyrics:"Valeriu Gafencu",
          music:"Dan Vasilescu(Trupa Acum)",
          videoLink: "https://www.youtube.com/embed/-AJrAem0YyA",
          id:7
        },
 {
          title:"Colindul robului 1",
          avatar:"https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQcbNVB6ZofywgxyNHqU6jjpJTX-URIUGuQwg&usqp=CAU",
          lyrics:"Valeriu Gafencu",
          music:"Dan Vasilescu(Trupa Acum)",
          videoLink: "https://www.youtube.com/embed/-AJrAem0YyA",
          id: 8
        },
 {
          title:"Colindul robului 1",
          avatar:"https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQcbNVB6ZofywgxyNHqU6jjpJTX-URIUGuQwg&usqp=CAU",
          lyrics:"Valeriu Gafencu",
          music:"Dan Vasilescu(Trupa Acum)",
          videoLink: "https://www.youtube.com/embed/-AJrAem0YyA",
          id: 12
        },
 {
          title:"Colindul robului 1",
          avatar:"https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQcbNVB6ZofywgxyNHqU6jjpJTX-URIUGuQwg&usqp=CAU",
          lyrics:"Valeriu Gafencu",
          music:"Dan Vasilescu(Trupa Acum)",
          videoLink: "https://www.youtube.com/embed/-AJrAem0YyA",
          id: 9
        },
 {
          title:"Colindul robului 1",
          avatar:"https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQcbNVB6ZofywgxyNHqU6jjpJTX-URIUGuQwg&usqp=CAU",
          lyrics:"Valeriu Gafencu",
          music:"Dan Vasilescu(Trupa Acum)",
          videoLink: "https://www.youtube.com/embed/-AJrAem0YyA",
          id: 10
        },
 {
          title:"Colindul robului 1",
          avatar:"https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQcbNVB6ZofywgxyNHqU6jjpJTX-URIUGuQwg&usqp=CAU",
          lyrics:"Valeriu Gafencu",
          music:"Dan Vasilescu(Trupa Acum)",
          videoLink: "https://www.youtube.com/embed/-AJrAem0YyA",
          id: 11
        },

      ]
    }
  }
}
</script>

<style scoped>
/*.links-top{*/
/*  font-weight: bold;*/
/*  font-size: 1.3rem;*/
/*}*/
.row-flex-wrap{
  display: flex;
  flex-wrap:wrap;
}
.display-flex-sb-main{
  display: flex;
  justify-content: space-between;
  align-content: center;
  padding: 10px 30px;
  background: var(--white);
  color: var(--white);
}
.columns {
  flex-grow: 1;
  min-width:250px;
  width: 300px;
  max-width: 450px;
  margin: .5rem;
}
.video-container{
  padding: .2rem .1rem;
  flex-grow: 1;
  display: flex;
  justify-content: center;
}
.video-link{
  height: 240px;
  width: 340px;
}
.border{
  border: 1px solid var(--grey-3, #ccc);
  /*height: 450px;*/
  margin: 1rem 0;
  /*min-width: 350px;*/
  flex-wrap: wrap;
}
.foto-link{
  padding: .3rem 1.2rem;
}
.foto-link p{
  /*margin-top: 5px;*/
  display: flex;
  justify-content: center;
  align-items: center;
  margin-right: 4.6rem;
}
.foto-link-img{
  border-radius: 50%;
  height: 3.3rem;
  width: 3.3rem;
}
.video-para{
  font-size: 1.3rem;
  color: var(--font-grey);
  font-family: 'Museo300_Regular', sans-serif;
  font-weight: bold;
}
.video-about{
  color: var(--black-1);
  font-weight: bolder;
  line-height: var(--lineHeight-1);
  padding: .1rem 1.2rem .8rem 1.2rem;
}
.video-title{
  color: var(--red-1);
  font-size: 1rem;
}
.video-music{
  color: var(--font-grey);
  font-size: 1rem;
}
@media screen and (max-width: 768px){
  .columns {
    width: 240px;
    min-width:200px ;
  }
  .border{
    height: 400px;
  }
  .video-link{
    height: 200px;
    width: 230px;
  }
}
#logo{
  height: 360px;
}
@media screen and (max-width: 550px){
  span.p15{
    padding: 0.1rem;
  }
  .links-top {
    font-size: 1rem;
  }
  .columns {
    width: 280px;
    min-width:220px ;
  }
  .border{
    height: 480px;
  }
  .video-link{
    height: 260px;
    width: 320px;
  }
  .foto-link p {
    margin: 0 1.9rem 0 .2rem;
  }
  .video-about{
    padding: 0.3rem 1.2rem .5rem 1.2rem;
  }
}
@media screen and (max-width: 400px){
  .columns {
    width: 280px;
    min-width:220px ;
  }
  .border{
    height: 480px;
  }
  .video-link{
    height: 260px;
    width: 310px;
  }
}
@media screen and (max-width: 320px){
  .columns {
    width: 280px;
    min-width:220px ;
  }
  .border{
    height: 450px;
  }
  .video-link{
    height: 260px;
    width: 260px;
  }
  .video-about{
    padding: 0.5rem 1.2rem .5rem  1.2rem ;
  }
  .video-para {
    margin: 0 1.2rem;
    font-size: 1rem;
  }
}
</style>