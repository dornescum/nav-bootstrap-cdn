<template>
  <nav class="navbar fixed-top navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
      <!--      <a class="navbar-brand" href="#">Navbar</a>-->
      <router-link id="logo" to="/">
        <img
            alt="logo"
            src="https://images.unsplash.com/photo-1568702846914-96b305d2aaeb?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80">
      </router-link>
      <button aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation" class="navbar-toggler"
              data-bs-target="#navbarSupportedContent" data-bs-toggle="collapse" type="button">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div id="navbarSupportedContent" class="collapse navbar-collapse">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">

          <li class="nav-item dropdown">
            <a id="navbarDropdown" aria-expanded="false" class="nav-link dropdown-toggle" data-bs-toggle="dropdown" href="#"
               role="button">
              Despre proiect
            </a>
            <ul aria-labelledby="navbarDropdown" class="dropdown-menu">
              <li>
                <router-link to="/about">About</router-link>
              </li>
              <li>
                <router-link to="/contact">Contact</router-link>
              </li>
          <li>
                <router-link to="/sustine">Sustine</router-link>
              </li>
<li>
                <router-link to="/bibliografie">Bibliografie</router-link>
              </li>
<li>
                <router-link to="/contact">Contact</router-link>
              </li>

              <li>
                <hr class="dropdown-divider">
              </li>
              <li>
                <router-link to="/videoteca">Videoteca</router-link>

              </li>
            </ul>
          </li>
          <li class="nav-item dropdown">
            <a id="navbarDropdown2" aria-expanded="false" class="nav-link dropdown-toggle" data-bs-toggle="dropdown" href="#"
               role="button">
             Bibliografie
            </a>
            <ul aria-labelledby="navbarDropdown" class="dropdown-menu">
              <li>
                <router-link to="/paginaArticol">Pagina Articol</router-link>
              </li>
              <li>
                <router-link to="/contact">Contact</router-link>
              </li>

              <li>
                <hr class="dropdown-divider">
              </li>
              <li>
                <router-link to="/bibliografie">Bibliografie</router-link>
              </li>
            </ul>
          </li>
          <li class="nav-item dropdown">
            <a id="navbarDropdown3" aria-expanded="false" class="nav-link dropdown-toggle" data-bs-toggle="dropdown" href="#"
               role="button">
             Sustine
            </a>
            <ul aria-labelledby="navbarDropdown" class="dropdown-menu">
              <li>
                <router-link to="/biografiePoet">Biografie Poet</router-link>
              </li>
              <li>
                <router-link to="/categorieArticole">Categorie Articole</router-link>
              </li>

              <li>
                <hr class="dropdown-divider">
              </li>
              <li>
                <router-link to="/bibliografie">Bibliografie</router-link>

              </li>
            </ul>
          </li>
          <li class="nav-item dropdown">
            <a id="navbarDropdown4" aria-expanded="false" class="nav-link dropdown-toggle" data-bs-toggle="dropdown" href="#"
               role="button">
              Contact
            </a>
            <ul aria-labelledby="navbarDropdown" class="dropdown-menu">
              <li>
                <router-link to="/">Sustine</router-link>
              </li>
              <li>
                <router-link to="/contact">Contact</router-link>
              </li>

              <li>
                <hr class="dropdown-divider">
              </li>
              <li>
                <router-link to="/testFetch">Test Fetch</router-link>
              </li>
            </ul>
          </li>
<!--          <li class="nav-item dropdown">-->
<!--            <a id="navbarDropdown5" aria-expanded="false" class="nav-link dropdown-toggle" data-bs-toggle="dropdown" href="#"-->
<!--               role="button">-->
<!--              Dropdown-->
<!--            </a>-->
<!--            <ul aria-labelledby="navbarDropdown" class="dropdown-menu">-->
<!--              <li>-->
<!--                <router-link to="/sustine">Sustine</router-link>-->
<!--              </li>-->
<!--              <li>-->
<!--                <router-link to="/contact">Contact</router-link>-->
<!--              </li>-->

<!--              <li>-->
<!--                <hr class="dropdown-divider">-->
<!--              </li>-->
<!--              <li>-->
<!--                <router-link to="/bibliografie">Bibliografie</router-link>-->

<!--              </li>-->
<!--            </ul>-->
<!--          </li>-->


        </ul>
        <form class="d-flex">
          <input aria-label="Search" class="form-control me-2" placeholder="Search" type="search" @input="addSearch">
          <button class="btn btn-outline-secondary" type="submit" id="search" @click="resetSearch">Search</button>
        </form>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: "TheNavbar",
  data(){
    return{
      enteredValue: '',
      search: []
    }
  },
  methods:{
    addSearch(e){
      this.enteredValue = e.target.value;
      console.log(e.target.value);
    },
    resetSearch(){
      this.enteredValue= ' ';
    }


  }
}
</script>

<style scoped>
a {
  color: var(--grey-1);
  padding: .5rem 1rem;
  text-decoration: none;
  /*transition: var(--transition);*/
}
a:hover{
  color: var(--grey-2);
  /*background: var(--grey-3);*/
}

#logo {
  padding: .3rem 1rem;
}

#logo img {
  height: 2.2rem;
  width: 2.7rem;
  border-radius: 5px;
}
a.router-link-exact-active {
  color: var(--black-1);
}
ul{
  /*transition: var(--transition);*/
}
ul li{
  padding: .5rem 1rem;
  /*background: var(--grey-3);*/
}
ul li:hover{
  padding: .5rem 1rem;
  background: var(--grey-3);
  transition: var(--transition);
}
#search:hover{
  background: var(--red-1);
}
.dropdown-toggle::after{
  color: red;
}
</style>