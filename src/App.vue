<template>
  <div id="app">
    <div id="nav">
<!--      <router-link to="/">Home</router-link> |-->
<!--      <router-link to="/about">About</router-link>-->
      <TheNavbar/>
    </div>
    <router-view/>
  </div>
</template>

<script>
import TheNavbar from "./components/Ui/TheNavbar";
export default {
  components:{
    TheNavbar
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
:root {
  --font-grey: #949494;
  --font-grey-1: #707070;
  --font-grey-2: #a5a5a5;

  --red-1: #e00000;
  --black-1: #000000;
  --grey-1: #969696;
  --grey-2: #8a8a8a;
  --grey-3: #f2f2f2;
  --grey-4: #f1efea;
  --grey-5: #adadad ;
  --grey-6: #f1f1f1 ;
  --silver-1: #e8e8e8;
  --black: #222;
  --white: #fff;
  --transition: all 0.3s linear;
  --transition-2: all 0.1s linear;
  --spacing: 0.1rem;
  --spacing-2: 1.2px;
  --radius: 0.25rem;
  --light-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
  --dark-shadow: 0 5px 15px rgba(0, 0, 0, 0.4);


  /*utils*/
  --lineHeight-1: 1.6rem;
  --lineHeight-2: 1.2rem;
  --line-spacing: 1.2px;
}

/*//colors*/
  .white-background {
    background: var(--white);
  }

.grey-background {
  background: var(--grey-4);
}

/*//font*/
  .font-20 {
    font-size: 20px;
  }
  .red-background{
    background: var(--red-1);
   padding: 3px;
  }
  .black-background{
    background: var(--black-1);
    padding: 2px;
  }

/*//padding*/
  .p-1 {
    padding: 1rem;
  }

.p-2 {
  padding: 2rem;
}

.p-3 {
  padding: 3rem;
}

.p-4 {
  padding: 4rem;
}

.p-5 {
  padding: 5rem;
}

.pb-1 {
  padding-bottom: 1rem;
}

.pt-1 {
  padding-top: 1rem;
}

/*//margin*/
  .mt-1 {
    margin-top: 1rem;
  }

.mt-2 {
  margin-top: 2rem;
}

.mb-1 {
  margin-bottom: 1rem;
}

.mb-2 {
  margin-bottom: 2rem;
}

.mb-3 {
  margin-bottom: 3rem;
}

.mb-4 {
  margin-bottom: 4rem;
}

.mb-5 {
  margin-bottom: 5rem;
}

.display-flex-sb{
  display: flex;
  justify-content: space-between;
  align-content: center;
  padding: 10px 30px;
  background: var(--red-1);
  color: var(--white);
}
.display-flex-ct{
  display: flex;
  justify-content: center;
  align-content: center;
  margin: 0;
}
.border-left{
  border-left: 1px solid var(--grey-3);
}

/*#nav {*/
/*  padding: 30px;*/
/*}*/

/*#nav a {*/
/*  font-weight: bold;*/
/*  color: #2c3e50;*/
/*}*/

/*#nav a.router-link-exact-active {*/
/*  color: #42b983;*/
/*}*/
</style>
