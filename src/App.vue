<template>
  <div id="app">
    <nav class="navbar navbar-expand-lg navbar-light bg-warning">
  <a class="navbar-brand" href="#">KenKash</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>

  <div class="collapse navbar-collapse" id="navbarSupportedContent">
    <ul class="navbar-nav ml-auto">
      <li class="nav-item active">
        <a class="nav-link" href="#">
          <i class="fa fa-coins" id="fa"></i>
          Offers <span class="sr-only">(current)</span></a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">
          <i class="fa fa-wallet" id="fa"></i>
          Wallet</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">
          <i class="fa fa-search-dollar" id="fa"></i>
          Buy</a>
      </li>
       <li class="nav-item">
        <a class="nav-link" href="#">
          <i class="fa fa-user-circle" id="fa"></i>
          Become an Agent</a>
      </li>
       <li class="nav-item">
        <a class="nav-link" href="#">
          <i class="fa fa-user-plus" id="fa"></i>
          Register</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">
          <i class="fa fa-sign-in-alt" id="fa"></i>
          Login</a>
      </li>
    </ul>
  </div>
</nav>
<Banner/>
<Highlight/>
<Contact/>
  </div>
</template>

<script>
import Banner from './components/Banner'
import Contact from './components/Contact'
import Highlight from './components/Highlight'

export default {
  name: 'App',
  components: {
    Banner,
    Highlight,
    Contact
  }
}
</script>

<style>
.nav-link,.navbar-brand{
  color:white !important;
  font-weight:bold;
}
#fa{
  color:blue;
  opacity: .7;
}
#app{
  overflow:hidden !important;
}
</style>
