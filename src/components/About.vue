<template>
  <div class="about">
    <div data-aos="fade-up" data-aos-duration="700" id="about" class="container mt-md-5 p-lg-3 pb-3">
      <div class="post-heading text-center">
      <h3 data-aos="fade-up" class="display-4">About Me</h3>
      <hr class="w-50 mx-auto pb-5">
      </div>
   <div class="row">
       <div class="col-lg-6 col-md-6 col-12">
           <img data-aos="fade-right" data-aos-duration="750" id="about-img" src="https://i.postimg.cc/bNL9qq1C/IMG-20221031-WA0016.jpg" class="img-fluid shadow mb-5 bg-white rounded">
       </div>
  
       <div data-aos="fade-left" data-aos-duration="700" class="col-lg-6 col-md-6 col-12">
          <h2 id="about2">I Develop and Design Websites</h2>
          <hr class="w-75">
          <p>When building a website what's key is responsiveness and simplicity,<br> i can provide clean code and pixel Perfect Design in all my work.<br> i also make websites feel more interactive with web Animations.<br> My responsive Design makes your website accessible to all users<br> regardless of their devices.</p>
  
           <router-link to="/work"><button class="more w-25 text-light">
           Testimonials
          </button></router-link>
       </div>
  
   </div>
  </div>
  
  </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
*,
*::after,
*::before{
    
    box-sizing:border-box;
    overflow-x: hidden;
    font-family: 'Dosis', sans-serif;
}

h2{
  font-weight: 400;
}

p{
  font-size: large;
}

.more{
  width: 60% !important;
  margin-left: 20%;
}

#about .more{
  border: 2px solid transparent !important;
  background-color: rgba(0, 0, 0, 0.8) !important;
  width: 40%;
  padding: 8px 18px;
  border-radius: 5px;
  margin-top: 13% !important;
}

#about .more a{
  color: whitesmoke !important;
  text-decoration: none !important;
}

#about .more:hover{
  border: 2px solid rgb(212, 175, 55) !important;
  color: rgb(212, 175, 55) !important;
  text-decoration: none !important;
  cursor: pointer;
}

@media only screen and (max-width: 721px){
 #about{
    margin-top: 13%;
  }
}

@media only screen and (max-width: 301px){
  h2{
    font-weight: 400;
  }
  
  p{
    font-size: large;
  }
  
  #about{
    margin-top: 23%;
  }

  #about .more{
    border: 2px solid transparent !important;
    background-color: rgba(0, 0, 0, 0.8) !important;
    width: 40%;
    padding: 8px 18px;
    border-radius: 5px;
  }
  
  #about .more a{
    color: whitesmoke !important;
    text-decoration: none !important;
  }
  
  #about .more:hover{
    border: 2px solid rgb(212, 175, 55) !important;
    color: rgb(212, 175, 55) !important;
    text-decoration: none !important;
    cursor: pointer;
  }
  
}

</style>