
<template>
<section class="topbar d-lg-flex text-white bg-transparent">
      <div class="container small-3">
        <nav class="nav">
          <a class="nav-link pl-0" href="#">About</a>
          <a class="nav-link" href="#">Contact</a>
          <a class="nav-link" href="#">Terms</a>
          <a class="nav-link" href="#">Policy</a>
          <a class="nav-link" href="#">Help</a>
        </nav>

        <div class="dropdown mr-4">
          <span class="dropdown-toggle" data-toggle="dropdown">English</span>
          <div class="dropdown-menu dropdown-menu-right">
            <a class="dropdown-item" href="#">English</a>
            <a class="dropdown-item" href="#">Spanish</a>
            <a class="dropdown-item" href="#">French</a>
          </div>
        </div>
      </div>
    </section><!-- /.topbar -->
    
  <div id="nav">
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link> |
    <router-link to="/contact">Contact Us</router-link>

     


  </div>
  <router-view/>
</template>


 

<style>
 
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>


