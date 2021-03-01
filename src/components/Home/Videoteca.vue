<template>
  <div class="container mb-2">
    <div class="display-flex-sb">
      <div class="video-title">
        <h3>Videoteca</h3>
      </div>
      <div class="video-section">
        <ul class="display-flex-ct">
          <li class="link-video">
            <a href="#">
              conferinte |
            </a>
           </li>
          <li class="link-video">
            <a href="#">  concerte |</a>
           </li>
          <li class="link-video">
            <a href="#"> documentare</a>
          </li>
        </ul>
      </div>
    </div>
  </div>

</template>

<script>
export default {
name: "Videoteca"
}
</script>

<style scoped>
.video-title{
  display: flex;
  justify-content: center;
  align-content: center;
  flex-wrap: wrap;
  font-size: 2.2rem;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Ubuntu, "Helvetica Neue", Helvetica, sans-serif;
  letter-spacing: var(--spacing);
}
.video-section{
  display: flex;
  justify-content: center;
  align-content: center;
  flex-wrap: wrap;
}
ul {
  list-style: none;
  font-size: 1.4rem;
}
.link-video{
  padding: 2px 7px;
  display: inline-block;
}
a{
  color: var(--white);
  text-decoration: none;
}
@media screen and (max-width: 768px){
  .display-flex-sb{
    flex-direction: column;
  }
  .display-flex-ct{
    flex-direction: column;
    font-size: 0.8rem ;
  }
  .video-title{
    font-size: 1.5rem;
  }
}
</style>