<template>
    <div>
        <nav class="navbar navbar-expand-lg navbar-light bg-light">
  <div class="container-fluid">
   
    <img id="logoNavbar" src="/img/logo.png" class="logo-sm">
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" aria-current="page" href="#">List Product</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" aria-current="page" href="#">About Us</a>
        </li>
      </ul>
      
    </div>
  </div>
</nav>
    </div>
</template>

<script>
    export default{
        name: "header"
    }
</script>

<style scoped>
    #logoNavbar{
        width: 60px;
        height: auto;
    }
</style>