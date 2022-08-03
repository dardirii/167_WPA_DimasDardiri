<template>
    <nav class="navbar navbar-expand-lg bg-light fixed-top">
  <div class="container">
    <router-link class="navbar-brand" to="/"><h3 class="text-muted">HEYYA</h3></router-link>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <router-link class="nav-link" to="/">Home</router-link>
        </li> 
        <li class="nav-item">
          <router-link class="nav-link" to="/about">About</router-link>
        </li> 
        <li class="nav-item">
          <a class="nav-link" href="#services">Services</a>
        </li> 
        <li class="nav-item">
          <a class="nav-link" href="#portofolio">Portofolio</a>
        </li> 
        <li class="nav-item">
          <a class="nav-link" href="#team">Team</a>
        </li> 
        <li class="nav-item">
          <a class="nav-link" href="#contact">Contact</a>
        </li> 
      </ul>
    </div>
  </div>
</nav>
</template>

<style scoped>
.navbar-nav a{
    font-size:15px;
    text-transform: uppercase;
    font-weight: 500;
}
.navbar-light .navbar-brand{
    color:#000;
    font-size: 25px;
    text-transform: uppercase;
    font-weight: 700;
    letter-spacing: 2px;
}

.navbar-light .navbar-brand:focus,
.navbar-light .navbar-brand:hover{
    color:#000;
}

.navbar-light .navbar-nav .navbar-link{
    color:#000;
}

.w-100 {
    height:100vh;
}

.navbar{
  box-shadow: 0 2px 4px 0 rgba(0,0,0,.2);
}
.navbar-brand h3{
  font-family: 'Geneva';
}

@media only screen and (max-width: 767px){
    .navbar-nav{
        text-align: center;
    }
}


</style>