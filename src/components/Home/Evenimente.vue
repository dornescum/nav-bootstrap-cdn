<template>
  <div>

    <div class="container evenimente-box">
      <p class="evenimente-btn">Evenimente</p>
      <div class="row mt-1 pt-2">

        <div class="col-sm-12 col-md-6 col-lg-4">
          <div class="picture-main">

            <img src="https://images.unsplash.com/photo-1593866422290-b72487fdf169?ixid=MXwxMjA3fDB8MHxzZWFyY2h8OXx8cHJpZXN0fGVufDB8fDB8&ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60" alt="some picture" class="picture-evenimete">
            <p class="evenimente-para">
              Transfigurarea suferinței prin rugăciune şi poezie - Mesajul Patriarhului Daniel la Colocviul de literatură creştină
            </p>
            <button class="btn-evenimente">
              citeste mai departe
            </button>
          </div>
        </div>
        <div class="col-sm-12 col-md-6 col-lg-4">
          <div class="picture-main">

            <img src="https://images.unsplash.com/photo-1593866422290-b72487fdf169?ixid=MXwxMjA3fDB8MHxzZWFyY2h8OXx8cHJpZXN0fGVufDB8fDB8&ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60" alt="some picture" class="picture-evenimete">
            <p class="evenimente-para">
              Transfigurarea suferinței prin rugăciune şi poezie - Mesajul Patriarhului Daniel la Colocviul de literatură creştină
            </p>
            <button class="btn-evenimente">
              citeste mai departe
            </button>
          </div>
        </div>
        <div class="col-sm-12 col-md-6 col-lg-4">
          <div class="picture-main">

            <img src="https://images.unsplash.com/photo-1593866422290-b72487fdf169?ixid=MXwxMjA3fDB8MHxzZWFyY2h8OXx8cHJpZXN0fGVufDB8fDB8&ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60" alt="some picture" class="picture-evenimete">
            <p class="evenimente-para">
              Transfigurarea suferinței prin rugăciune şi poezie - Mesajul Patriarhului Daniel la Colocviul de literatură creştină
            </p>
            <button class="btn-evenimente">
              citeste mai departe
            </button>
          </div>
        </div>

      </div>
    </div>
  </div>
</template>

<script>
export default {
name: "Evenimente"
}
</script>


<style scoped>
.evenimente-box{
  background: var(--grey-4);
}
p{
  line-height: var(--lineHeight-1);
}
.btn-evenimente{
  border: 1px solid var(--black-1);
  color: var(--red-1);
  font-size: 0.9rem;
  padding: 5px 10px;
  /*background-color: var(--grey-2);*/
  display: flex;
  justify-content: start;
}
.btn-evenimente:hover{
  background: var(--white);
}
.picture-main{
  padding: 1rem;
}
.picture-evenimete{
  height: 250px;
  max-width: 100%;
  padding-bottom: 1rem;
}
.evenimente-btn{
  background: var(--black-1);
  color: var(--white);
  display: inline-block;
  padding: 5px 25px;
  text-transform: uppercase;
  font-size: 1rem;
  margin-bottom: 0;
}
.evenimente-para{
  line-height: var(--lineHeight-1);
  font-size: 1.4rem;
  font-weight: 500;
  color: var(--black-1);
  letter-spacing: var(--spacing-2);
  margin: 0;
  padding: 1rem 0;

}
@media screen and (max-width: 420px) {
  .evenimente-box{
    padding: 5px;
  }
  .picture-main{
    padding: 0.5rem 0.5rem 1rem 0.5rem;
  }
  .picture-main img{
    margin-bottom: 1rem;
  }
  p{
    font-size: 1rem;
  }
}
</style>