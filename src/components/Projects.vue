<template>
  <div data-aos="fade-up" data-aos-duration="700" id="skills" class="container text-center">
    <h3 id="Exp" class="display-4 mt-5">Projects</h3>
    <hr class="w-50 mx-auto pb-5">
  </div>
  <div data-aos="fade-up" data-aos-duration="900" class="card-holder">
    <div class="card" style="width: 18rem" v-for="duck in products" :key="duck">
      <img :src="duck.img" class="card-img-top img-fluid" alt="" />
      <div class="card-body">
        <h5 class="card-title" v-text="duck.brand"></h5>
        <p class="card-text" v-text="duck.model"></p>
        <a class="link" :href="duck.price">Go to site</a>
      </div>
    </div>

  </div>
</template>

<script>

export default {
  data() {
    return {
      products: [
        {
          id: "A",
          brand: "Manga Shop",
          price: "https://eccomerce111111.netlify.app",
          model: "Here is my example of a eCommerce website with a simple strate to the point design.",
          img: "https://i.postimg.cc/mkpywHkf/Screenshot-Ecommers.jpg",
        },
        {
          id: "B",
          brand: "Eg Blog",
          price: "https://3log.netlify.app",
          model: "This is another project which is blog based, the idea is to make customers want to try products advertised.",
          img: "https://i.postimg.cc/Y2LNKhv9/Screenshot-20221105-121118.png",
        },
        {
          id: "C",
          brand: "Eg Calculator",
          price: "https://harmonious-calculator.netlify.app",
          model: "A basic calculator built using JavaScript and CSS which can perform simple non-scientific calculations.",
          img: "https://i.postimg.cc/15JTtyxb/Screenshot-2023-01-12-121551.jpg",
        },
        {
          id: "D",
          brand: "Sound Vibe",
          price: "https://soundvibepremuim.netlify.app",
          model: "A eCommerce site with a functional check function and and admin table.",
          img: "https://i.postimg.cc/gJVtPWqS/Screenshot-2023-01-12-121346.jpg",
        },
        {
          id: "E",
          brand: "Eg Portfolio",
          price: "https://egportfolio1.netlify.app",
          model: "This is a example of a simple portfolio that highlights the main key-points of a profile.",
          img: "https://i.postimg.cc/k5VN1MmZ/Screenshot-Matrics.png",
        },
        {
          id: "F",
          brand: "Joke Generator",
          price: "https://chucknorrisjokes.netlify.app",
          model: "Simple generator project which gives chuck Norris jokes every time the page is reloaded",
          img: "https://i.postimg.cc/LXfxDcgz/Screenshot-2023-01-13-162746.jpg",
        },
      ],
    };
  },
};

//
</script>

<style scoped>
*,
*::after,
*::before{
   
    box-sizing:border-box;
    overflow-x: hidden;
    font-family: 'Dosis', sans-serif;
}
  .card-holder{
    display: flex;
    flex-wrap: wrap;
    justify-content: space-evenly;
  }
  .card{
    width: 18rem;
    border: 1px solid black;
    margin-bottom: 2%;
  }
  .card-img-top{
    width: 18rem;
  }

  .link{
    color: rgb(163, 133, 32);
    text-decoration-line: none;
  }

  @media only screen and (max-width: 301px){
    .card-holder{
      display: flex;
      flex-wrap: wrap;
      justify-content: space-evenly;
    }
    .card{
      width: 18rem;
      border: 1px solid black;
      margin-bottom: 2%;
    }
    .card-img-top{
      width: 18rem;
    }
  
    .link{
      margin-left: 36%;
      color: rgb(163, 133, 32);
      text-decoration-line: none;
    }
  }
</style>
