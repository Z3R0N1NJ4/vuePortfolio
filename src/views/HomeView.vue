<template>
  <div class="home">
    <img class="home-image" alt="Vue logo" src="https://i.postimg.cc/FRZ70Hrw/49209786-380196372738578-5359558541852016640-n.jpg">
  </div>
  <div data-aos="fade-up" data-aos-duration="750" class="container heading text-center">
    <h5>Hi There, i'm</h5>
    <h1>Mishaine Isaacs</h1>
    <p>I'm a Web Developer</p>
 </div>
</template>

<script>

</script>

<style scoped>
*,
*::after,
*::before{
    margin: 0;
    padding: 0;
    box-sizing:border-box;
    overflow-x: hidden;
    font-family: 'Dosis', sans-serif;
}

.heading{
  position: absolute;
  top: 56%;
  width: 100%;
  min-width: 100%;
}

.heading h5{
   font-size: 3em;
   font-weight: 300;
   color: white !important;
}

.heading h1{
   font-size: 5em;
   font-weight: bolder;
   color: whitesmoke !important;
}

.heading p{
   font-size: 2rem;
   font-weight: 300;
   color: whitesmoke !important;
}

.home-image {
  position: fixed;
  width: 100%;
  animation: 9.5s ease 3s infinite beat;
}

@keyframes beat {
  0%, 50%, 100% { transform: scale(1, 1); }
  30%, 80% { transform: scale(1.03, 1.04); }
}

@keyframes pulse {
  0%, 50%, 100% {  background: rgba(0, 0, 0, 0.66); }
  30%, 80% { background: rgba(0, 0, 0, 0.66); }
}

@media only screen and (max-width: 721px){
  .heading{
    position: relative;
    margin-top: 25%;
    width: 100%;
    min-width: 100%;
  }
  
  .heading h5{
     font-size: 1.5em;
     font-weight: 300;
     color: white !important;
  }
  
  .heading h1{
     font-size: 2.5em;
     font-weight: bolder;
     color: whitesmoke !important;
  }
  
  .heading p{
     font-size: 1.5rem;
     font-weight: 300;
     color: whitesmoke !important;
  }
  
  .home-image {
    position: fixed;
    width: 100%;
    margin-top: 8.9%;
    animation: 9.5s ease 3s infinite beat;
  }
  
}

@media only screen and (max-width: 721px){
  .heading{
    position: relative;
    margin-top: 45%;
    width: 100%;
    min-width: 100%;
  }
  
  .heading h5{
    position: relative;
     font-size: 2.5em;
     font-weight: 300;
     color: white !important;
  }
  
  .heading h1{
    position: relative;
     font-size: 3.5em;
     font-weight: bolder;
     color: whitesmoke !important;
  }
  
  .heading p{
    position: relative;
     font-size: 2.5rem;
     font-weight: 300;
     color: whitesmoke !important;
  }
  
  .home-image {
    position: fixed;
    height: auto;
    width: 100%;
    margin-top: 8.8%;
    animation: 9.5s ease 3s infinite beat;
  }
  
}

@media only screen and (max-width: 301px){
  .heading{
    position: relative;
    margin-top: 40%;
    width: 100%;
    min-width: 100%;
  }
  
  .heading h5{
    position: relative;
     font-size: 1.5em;
     font-weight: 300;
     color: white !important;
  }
  
  .heading h1{
    position: relative;
     font-size: 2.5em;
     font-weight: bolder;
     color: whitesmoke !important;
  }
  
  .heading p{
    position: relative;
     font-size: 1.5rem;
     font-weight: 300;
     color: whitesmoke !important;
  }
  
  .home-image {
    position: fixed;
    height: 100%;
    width: auto;
    margin-top: 21.4%;
    animation: 9.5s ease 3s infinite beat;
  }
  
}

  
</style>
