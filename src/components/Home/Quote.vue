<template>
  <div class="container">
    <div class="grey-background"></div>
    <div class="row quote">
      <div class="col-sm-12 col-md-3 col-lg-4 white-background quoteName">
        <p id="quote">Virgil <span class="uppercase" >Mateiaș</span></p>
      </div>
      <div class="col-sm-12 col-md-9 col-lg-8 white-background quotePara">
        <p class="font-20">Poezia de detenție cu tematică carcerală nu este altceva decât o istorie în versuri, care a fost mai ușor de ascuns de vigilența paznicilor, de barbaria perchezițiilor, de suspiciunea anchetatorilor și deci, mai lesne de adus la lumină.</p>
      </div>
    </div>
  </div>
</template>


<script>
export default {
name: "Quote"
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=MuseoModerno:wght@100&display=swap');
#quote{
  color: var(--red-1);
  font-size: 28px;
  font-weight:100;
  /*font-family: Verdana;*/

}
.quote{
  margin: 35px auto;
  padding: 12px 0;
  background: var(--grey-6);

}
.quoteName{
  display: flex;
  justify-content: center;
  align-content: center;
  padding: 4rem;

}
.uppercase{
  text-transform: uppercase;
  font-weight: 300;
}
.quotePara{
  padding: 3rem;
  font-size: 34px;
}
.quotePara p{
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Ubuntu, "Helvetica Neue", Helvetica, sans-serif;
  font-style: italic;
  font-family: sans-serif;
  line-height: var(--lineHeight-1);
  color: var(--black);
}

@media screen and (max-width: 1280px) {
  #quote{
    font-size: 1.2rem;
  }
}
@media screen and (max-width: 992px) {
  #quote{
    font-size: 1rem;
  }
}
@media screen and (max-width: 768px) {
  #quote{
    font-size: 1.2rem;
  }
  .quoteName{
    padding: 1rem 1.5rem;
  }
  .quotePara{
    padding: 1rem 1.5rem;
  }
}
/*.grey-background{*/
/*  background: var(--grey-4);*/
/*}*/

</style>