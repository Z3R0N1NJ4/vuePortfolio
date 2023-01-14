<template>
  <header>
    <nav class="navbar navbar-expand-sm navbar-dark fixed-top">
      <button
      class="navbar-toggler ms-2 px-1"
      type="button"
      data-bs-toggle="collapse"
      data-bs-target="#navbarSupportedContent"
      aria-controls="navbarNavDropdown"
      aria-expanded="false"
      aria-label="Toggle navigation">
       <span class="navbar-toggler-icon"></span>
     </button>
   <div class="collapse navbar-collapse" id="navbarSupportedContent">
       <ul class="navbar-nav mx-auto">
         <li class="nav-item">
           <router-link to="/" class="nav-link text-light" aria-current="page" href="#home">Home</router-link>
         </li>
         <li class="nav-item dropdown">
           <li class="nav-item">
             <router-link to="/about" class="nav-link text-light" href="#about">About</router-link>
           </li>
         </li>
         <li class="nav-item">
           <router-link to="/projects" class="nav-link text-light" href="#skills">Skills</router-link>
         </li>
         <li class="nav-item">
           <router-link to="/contact" class="nav-link text-light" href="#contact">Contact</router-link>
         </li>
       </ul>
   </div>
</nav>
</header>

</template>

<script>
export default {
    
}
</script>

<style scoped>


.navbar{
  height: 4rem;
  text-transform: uppercase;
  font-size: 17px;
  font-weight: 600;
  letter-spacing: 0.2rem;
  background: rgba(0, 0, 0, 0.66) !important;
  padding: 15px 0 !important;
}

.navbar-dark .navbar-nav .nav-link{
  color: whitesmoke;
  padding-left: 20px !important;
}

.nav-link:hover{
  color:rgb(212, 175, 55) !important;
}

@media only screen and (max-width: 301px){
  .navbar{
    height: 4rem;
    text-transform: uppercase;
    font-size: 17px;
    font-weight: 600;
    letter-spacing: 0.2rem;
    background: rgba(0, 0, 0, 0.66) !important;
    padding: 15px 0 !important;
  }
  
  .navbar-dark .navbar-nav .nav-link{
    position: relative;
    color: rgb(133, 106, 14) !important;
    padding-left: 20px !important;
  }
  
  .nav-link:hover{
    color:rgb(212, 175, 55) !important;
  }
}

</style>