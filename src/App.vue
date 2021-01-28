<template>
  <div id="nav">
    <router-link to="/redirect"><img class="logo" src="@/assets/logo.svg"></router-link>
    <div class="link">
    <router-link to="/">Home</router-link>
    <router-link to="/about">About</router-link>
    <router-link to="/contact">Contact</router-link>
    </div>
  </div>
  <router-view/>
    <Footer/>
</template>


<script>
import Footer from './components/Footer'
export default {
  components: { Footer }
}
</script>

<style>
body{
  margin: 0px;
    font-family: 'Inter', sans-serif;
    color: #4f3a65;

}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /* text-align: center; */
      color: #4f3a65;

}


#nav a {
  font-weight: bold;
     color: #4f3a65;

}

#nav a.router-link-exact-active {
  color: #25CED8;
}
#nav{
  display: flex;
  width: 100%;
  background-color: white;
  height: 60px;
  box-shadow: .1px .1px 5px 0.1px gray;
  justify-content: space-between;
  align-items: center;
  position: fixed;
  z-index: 10;
}
.link a{
  padding: 20px;
  text-decoration: none;
}
.logo{
  padding: 18px;
  width: 130px;
}
</style>
