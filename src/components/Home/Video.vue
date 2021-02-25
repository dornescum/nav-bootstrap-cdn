<template>
  <div class="container">
    <div class="row pt-2 pb-2">
      <div class="col-sm-12 col-md-6 col-lg-4 border-left">
        <div class="video-container">
<!--          <video width="320" height="240" controls>-->
<!--            <source src="movie.mp4" type="video/mp4">-->
<!--            <source src="movie.ogg" type="video/ogg">-->
<!--            Your browser does not support the video tag.-->
<!--          </video>-->
          <iframe width="380" height="240"
                  src="https://www.youtube.com/embed/tgbNymZ7vqY" class="video-main">
          </iframe>
          <div class="video-link">
            <a href="#">Video  </a>
          </div>
          <p class="video-para">Cu Iisus in celula (concert Tudor Gheorghe)</p>
        </div>


      </div>
      <div class="col-sm-12 col-md-6 col-lg-4 border-left">
        <div class="video-container">
          <!--          <video width="320" height="240" controls>-->
          <!--            <source src="movie.mp4" type="video/mp4">-->
          <!--            <source src="movie.ogg" type="video/ogg">-->
          <!--            Your browser does not support the video tag.-->
          <!--          </video>-->
          <iframe width="380" height="240"
                  src="https://www.youtube.com/embed/tgbNymZ7vqY" class="video-main">
          </iframe>
          <div class="video-link">
            <a href="#">Video  </a>
          </div>
          <p class="video-para">Dan Vasilescu (Trupa Acum) - Colindul robului de Valeriu Gafencu</p>
        </div>


      </div>
      <div class="col-sm-12 col-md-12 col-lg-4 border-left">
            <div class="more-video">
              <h3 class="more-video-title">ALTE INTERPRETARI</h3>
              <ul class="video-ul">
                <li class="video-li">Avem o țară (de Radu Gyr)- interpretează maicile de la Mănăstirea Dervent
                </li>
                <li class="video-li">Colind (de Radu Gyr)
                </li>
                <li class="video-li">Cedry2k - Ridică-te, Gheorghe, ridică-te, Ioane! de Radu Gyr
                </li>
                <li class="video-li">Îndemn la luptă - Radu Gyr
                </li>
              </ul>
            </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
name: "Video"
}
</script>

<style scoped>
.video-container{
  padding: 1rem;
}
.video-link{
  display: flex;
  justify-content: start;
  padding: 5px 0 5px 2px;
}
.video-link a{
  color: var(--red-1);
  text-decoration: none;
  text-align: start;

}
.video-para{
  /*padding-left: 1rem;*/
  font-size: 2rem;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Ubuntu, "Helvetica Neue", Helvetica, sans-serif;
  letter-spacing: var(--spacing-2);
  padding: 0;
  /*display: flex;*/
  /*justify-content: start;*/
  text-align: start;
}
.more-video{
  padding: 1rem;

}
.more-video-title{
  font-size: 1.5rem;
  color: var(--red-1);
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Ubuntu, "Helvetica Neue", Helvetica, sans-serif;
  text-align: start;
}
.video-ul{
list-style: none;
  text-align: start;
  padding: 1rem 0 0 0;
}
.video-li{
  text-align: start;
  margin-bottom: 2rem;
  font-size: 1.4rem;
  line-height: var(--lineHeight-1);
}
@media screen and (max-width: 1440px){
  .video-main{
    height: 240px;
    width: 300px;
  }
}
@media screen and (max-width: 1200px){
  .video-main{
    height: 240px;
    width: 260px;
  }
}
/*@media screen and (max-width: 992px){*/
/*  .video-main{*/
/*    height: 240px;*/
/*    width: 260px;*/
/*  }*/
/*}*/
@media screen and (max-width: 768px){
  .video-main{
    height: 260px;
    width: 380px;
  }
}
@media screen and (max-width: 499px){
  .video-main{
    height: 260px;
    width: 280px;
  }
}
</style>