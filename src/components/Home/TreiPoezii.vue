<template>
  <div class="container">
    <div class="row pt-2 pb-2">
      <div class="col-sm-12 col-md-6 col-lg-4 border-left">
        <div class="poezii">
          <p class="titlu-poet">RADU GYR</p>
          <a href="#" class="titlu-poezie">Știu că sunt lut</a>
          <p>Ştiu că sunt lut, dar nu ştiu cine mi-a pus în piept albine stranii, să-mi scoată mir din mărăcine, din bălării, împărtăşanii.</p>
          <p>Minunea mea se-ntâmplă vie din mofturi mici şi biete fleacuri… Un colţ de-al meu e-o-mpărăţie, o zi de-a mea răsfrânge veacuri. </p>
          <p>De nu strâng mările în braţe, prin câte-o baltă tot deretic și gheara mea tot stă să-nhaţe din orice taină câte-un petic.</p>
          <p>Și dacă-ncălecat pe-o rază ea nu mă urcă-n cer, încalțe</p>

        </div>
        <div class="pt-1 pb-1">
          <a href="#" class="link-general">citeste mai mult  </a>
        </div>


      </div>
      <div class="col-sm-12 col-md-6 col-lg-4 border-left">
        <div class="poezii">
          <p class="titlu-poet">NICHIFOR CRAINIC</p>
          <a href="#" class="titlu-poezie">Unde sunt cei care nu mai sunt</a>
          <p>Întrebat-am vîntul, zburătorul Bidiviu pe care-aleargă norul Către-albastre margini de pămînt: Unde sînt cei care nu mai sînt? Unde sînt cei care nu mai sînt?</p>
          <p>Zis-a vîntul: Aripile lor Mă doboară nevăzute-n zbor. </p>
          <p>întrebat-am luminata ciocîrlie, Candelă ce leagănă-n tărie Untdelemnul cîntecului sfînt: Unde sînt cei care nu mai sînt? Unde sînt cei care nu mai sînt?</p>
          <p>Zis-a ciocîrlia: S-au ascuns În lumina celui nepătruns.</p>

          <!--        <a href="#" class="link-general">citeste mai mult  </a>-->

        </div>
        <div class="pb-1">
          <a href="#" class="link-general">citeste mai mult  </a>
        </div>

      </div>
      <div class="col-sm-12 col-md-12 col-lg-4 border-left">
        <div class="poezii">
          <p class="titlu-poet">TRAIAN DORZ</p>
          <a href="#" class="titlu-poezie">Blândul Păstor</a>
          <p>Odată L-am văzut trecând Cu turma pe Păstorul Blând. Mergea cu turma la izvor, Blândul Păstor, Blândul Păstor.</p>
          <p>Pe-o oaie ce căzuse jos, A ridicat-o El frumos; Şi-a dus-o-n braţe iubitor Blândul Păstor, Blândul Păstor. </p>
          <p>Pe alta care la pământ Zăcea cu picioruşul frânt, El o lega mângâietor Blândul Păstor, Blândul Păstor.</p>
          <p>Iar mai târziu L-am întâlnit, Cu spini era împodobit Într-o mulţime de popor</p>

        </div>
        <div class="pt-1 pb-1">
          <a href="#" class="link-general">citeste mai mult  </a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
name: "TreiPoezii"
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@100&display=swap');
/*.border-left{*/
/*  border-left: 1px solid var(--grey-3);*/
/*}*/
.poezii{
  /*border-left: 1px solid black;*/
  /*display: flex;*/
  /*flex-direction: column;*/
  /*justify-content: center;*/
  /*align-content: center;*/
  text-align: left;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Ubuntu, "Helvetica Neue", Helvetica, sans-serif;
  font-size: 19px;
}
.poezii p{
  margin: 5px 10px;
  padding: 5px 40px;
  font-size: 1.2rem;
  line-height: var(--lineHeight-1);
}
.titlu-poet{
  color: var(--red-1);
  font-size: 1rem;
  padding: 5px 10px;
  margin: 0 10px;
}

a {
  font-size: 1.5rem;
  color: var(--black-1) !important;
  padding: 5px 40px;
  margin: 0 10px;
  text-decoration: none;
}
.titlu-poezie{
  max-width: 400px;
}

.link-general{
  font-size: 1rem;
}
@media screen and (max-width: 420px) {
  .poezii p{
    padding: 5px;
    font-size: 1rem;
    line-height: var(--lineHeight-2);
  }
  .titlu-poet{
    padding: 5px;
  }
  a{
    padding: 5px;
  }
}
</style>