<template>
  <div class="container">
    <ul class="bottom-nav mt-3">

      <div class="dropdown">
        <button id="BottomNav1" aria-expanded="false" class="dropdown-toggle bottom-btn"
                data-bs-toggle="dropdown"
                type="button">
          Poetii
        </button>
        <ul aria-labelledby="dropdownMenuButton1" class="dropdown-menu dropdown-btn">
          <li>
            <router-link to="/about">About</router-link>
          </li>
          <li>
            <router-link to="/about">About</router-link>
          </li>
          <li>
            <router-link to="/contact">Contact</router-link>
          </li>
          <li>
            <router-link to="/bibliografie">Bibliografie</router-link>
          </li>
        </ul>
      </div>

      <div class="dropdown">
        <button id="BottomNav2" aria-expanded="false" class="dropdown-toggle bottom-btn"
                data-bs-toggle="dropdown"
                type="button">
          Poetii
        </button>
        <ul aria-labelledby="dropdownMenuButton1" class="dropdown-menu dropdown-btn">
          <li>
            <router-link to="/about">About</router-link>
          </li>
          <li>
            <router-link to="/about">About</router-link>
          </li>
          <li>
            <router-link to="/contact">Contact</router-link>
          </li>
          <li>
            <router-link to="/bibliografie">Bibliografie</router-link>
          </li>
        </ul>
      </div>

      <div class="dropdown">
        <button id="BottomNav3" aria-expanded="false" class="dropdown-toggle bottom-btn"
                data-bs-toggle="dropdown"
                type="button">
          Poetii
        </button>
        <ul aria-labelledby="dropdownMenuButton1" class="dropdown-menu dropdown-btn">
          <li>
            <router-link to="/about">About</router-link>
          </li>
          <li>
            <router-link to="/about">About</router-link>
          </li>
          <li>
            <router-link to="/contact">Contact</router-link>
          </li>
          <li>
            <router-link to="/bibliografie">Bibliografie</router-link>
          </li>
        </ul>
      </div>

      <div class="dropdown">
        <button id="BottomNav4" aria-expanded="false" class="dropdown-toggle bottom-btn"
                data-bs-toggle="dropdown"
                type="button">
          Poetii
        </button>
        <ul aria-labelledby="dropdownMenuButton1" class="dropdown-menu dropdown-btn">
          <li>
            <router-link to="/about">About</router-link>
          </li>
          <li>
            <router-link to="/about">About</router-link>
          </li>
          <li>
            <router-link to="/contact">Contact</router-link>
          </li>
          <li>
            <router-link to="/bibliografie">Bibliografie</router-link>
          </li>
        </ul>
      </div>

      <div class="dropdown">
        <button id="BottomNav5" aria-expanded="false" class="dropdown-toggle bottom-btn"
                data-bs-toggle="dropdown"
                type="button">
          Poetii
        </button>
        <ul aria-labelledby="dropdownMenuButton1" class="dropdown-menu dropdown-btn">
          <li>
            <router-link to="/about">About</router-link>
          </li>
          <li>
            <router-link to="/about">About</router-link>
          </li>
          <li>
            <router-link to="/contact">Contact</router-link>
          </li>
          <li>
            <router-link to="/bibliografie">Bibliografie</router-link>
          </li>
        </ul>
      </div>


    </ul>
  </div>


</template>

<script>
export default {
  name: "BottomNav"
}
</script>

<style scoped>
.bottom-nav {
  display: flex;
  justify-content: space-around;
  align-content: center;
  padding: 2px 0px;
}

ul li {
  /*position: relative;*/
  display: flex;
  justify-content: center;
  align-content: center;
  text-align: center;
  /*max-width: 267px;*/
  width: 100%;
  padding: 2px 3px;
  transition: var(--transition);
  /*color: var(--grey-3);*/

}

a {
  padding: 10px;
  background: var(--grey-6);
  width: 200px;
  transition: var(--transition);
  color: var(--grey-1) !important;
}

a:hover {
  background: var(--silver-1);
}

.bottom-btn {
  width: 220px;
  background: var(--grey-6);
  border-radius: 0;
  border: none;
  outline: none;
}

.dropdown-btn {
  width: 270px;
  background: var(--grey-6);
  border-radius: 0;

}

/*@media screen and (max-width: 1440px){*/
/* .bottom-btn {*/
/*    width: 200px;*/
/*  }*/
/*}*/
@media screen and (max-width: 1300px){
  .bottom-btn {
    width: 180px;
  }
}
@media screen and (max-width: 1200px){
  .bottom-btn {
    width: 150px;
  }
}
@media screen and (max-width: 1100px){
  .bottom-btn {
    width: 130px;
  }
}
@media screen and (max-width: 992px){
  .bottom-btn{
    width: 100px;
    padding: 5px;
  }
}
@media screen and (max-width: 768px){
  ul {
    flex-direction: column;
  }
  li{
    width: 100%;
    display: block;
    padding: 5px;

  }
  .bottom-btn {
    width: 100%;
    padding: 5px 0 5px 0;
    font-size: 14px;
    background: var(--grey-6);
  }
}
@media screen and (max-width: 599px){
  .bottom-btn {
    padding: 3px;
    font-size: 12px;
  }
}
@media screen and (max-width: 400px){
  a {

    padding: 5px;
    font-size: 12px;
  }
  ul{
    margin: 1px;
  }
  ul li a{
    padding: 2px;
  }
}

</style>