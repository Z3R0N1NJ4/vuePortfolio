<template>
  <div data-aos="fade-up" data-aos-duration="700" id="contact" class="text-center">
    <h3 id="Exp" class="display-4 font-weight-bold mt-5">Connect With Me</h3>
    <hr class="w-50 mx-auto pb-5">
  </div>
  <form action="mailto:www.beakerbreaker19@gmail.com">
  <div data-aos="fade-up" data-aos-duration="900" class="contact">
  <div class="container">
  <div class="mb-3">
    <label for="exampleFormControlInput1" class="form-label m-1">Full Name</label>
    <input type="text" class="form-control" id="exampleFormControlInput1" placeholder="Name">
  </div>

  <div class="mb-3">
    <label for="exampleFormControlInput1" class="form-label m-1">Cell No.</label>
    <input type="number" class="form-control" id="exampleFormControlInput1" placeholder="Cell No.">
  </div>
  <div class="mb-3">
    <label for="exampleFormControlInput1" class="form-label m-1">Email address</label>
    <input type="email" class="form-control" id="exampleFormControlInput1" placeholder="Email">
  </div>
  <div class="mb-3">
    <label for="exampleFormControlTextarea1" class="form-label m-1">Let Me Know What You're Looking For</label>
    <textarea class="form-control" id="exampleFormControlTextarea1" rows="3"></textarea>
  </div>
  <div  id="btn" class="col-auto">
    <button type="submit" class="btn btn-primary mb-3 px-4 m-1">Submit</button>
  </div>
</div>

<div><img class="contact-img" src="https://i.postimg.cc/9Qr47McD/DSC-3511-JPGcrop.jpg" width="75%"></div>
</div>
</form>
  
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

#btn{
  margin-left: 30%;
}

.container{
  width: 45%;
  margin-left: 6%;
  margin-top: 7%;
  justify-content: center;
}

.contact{
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
}

.contact-img{
overflow: hidden;
justify-content: center;
margin-left: 12.5% !important;
}

@media only screen and (max-width: 721px){
  #contact{
    margin-top: 8% !important;
  }
}
  
@media only screen and (max-width: 301px){

  #contact{
    margin-top: 13%;
  }
  .container{
    width: 88%;
    margin-left: 6%;
    margin-top: 7%;
    justify-content: center;
  }
  
  .contact{
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
  }
  
  .contact-img{
  overflow: hidden;
  justify-content: center;
  margin: 10%;
  }
}
</style>