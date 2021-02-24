<template>
  <ul class="bottom-nav">

    <div class="dropdown">
      <button id="BottomNav1" aria-expanded="false" class="btn dropdown-toggle bottom-btn"
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
  padding: 2px 5px;
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
  width: 225px;
  transition: var(--transition);
  color: var(--grey-1) !important;
}

a:hover {
  background: var(--silver-1);
}
.bottom-btn{
  width: 270px;
  background: var(--grey-6);
  border-radius: 0;
  outline: none;
}
.dropdown-btn{
  width: 270px;
  background: var(--grey-6);
  border-radius: 0;

}

/*@media screen and (max-width: 1440px){*/
/*  a {*/
/*    width: 200px;*/
/*  }*/
/*}*/
/*@media screen and (max-width: 1300px){*/
/*  a {*/
/*    width: 180px;*/
/*  }*/
/*}*/
/*@media screen and (max-width: 1200px){*/
/*  a {*/
/*    width: 150px;*/
/*  }*/
/*}*/
/*@media screen and (max-width: 1100px){*/
/*  a {*/
/*    width: 130px;*/
/*  }*/
/*}*/
/*@media screen and (max-width: 992px){*/
/*  a {*/
/*    width: 100px;*/
/*    padding: 5px;*/
/*  }*/
/*}*/
/*@media screen and (max-width: 768px){*/
/*  ul {*/
/*    flex-direction: column;*/
/*  }*/
/*  li{*/
/*    width: 100%;*/
/*    display: block;*/
/*  }*/
/*  a {*/
/*    width: 100%;*/
/*    padding: 3px;*/
/*    font-size: 14px;*/
/*    background: var(--grey-2);*/
/*  }*/
/*}*/
/*@media screen and (max-width: 599px){*/
/*  a {*/

/*    padding: 3px;*/
/*    font-size: 12px;*/
/*  }*/
/*}*/
/*@media screen and (max-width: 400px){*/
/*  a {*/

/*    padding: 3px;*/
/*    font-size: 12px;*/
/*  }*/
/*  ul{*/
/*    margin: 1px;*/
/*  }*/
/*  ul li{*/
/*    padding: 2px;*/
/*  }*/
/*}*/

</style>