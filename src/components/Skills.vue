<template>
    <div data-aos="fade-up" data-aos-duration="700" id="skills" class="container text-center">
        <h3 id="Exp" class="display-4 font-weight-bold mt-5">Skills</h3>
        <hr class="w-50 mx-auto pb-5">
      </div>
      <div data-aos="fade-up" data-aos-duration="900" class="card-holder">
        <div class="card" style="width: 18rem" v-for="duck in products" :key="duck">
          <img :src="duck.img" class="card-img-top img-fluid" alt="" />
          <div class="card-body">
            <h5 class="card-title" v-text="duck.brand"></h5>
            <p class="card-text" v-text="duck.model"></p>
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
              brand: "HTML",
              price: 27900,
              model: "The HyperText Markup Language or HTML is the standard markup language for documents designed to be displayed in a web browser.",
              img: "https://i.postimg.cc/j20FfrVy/HTML5-logo-and-wordmark-svg.png",
            },
            {
              id: "B",
              brand: "Cascading Style Sheets",
              price: 140000,
              model: "CSS is a style sheet language used for describing the presentation of a document written in a markup language such as HTML or XML",
              img: "https://i.postimg.cc/q7GRSpwv/CSS3-logo-and-wordmark-svg.png",
            },
            {
              id: "C",
              brand: "JavaScript",
              price: 1380000,
              model: "JS is a dynamic computer programming language. It is lightweight and most commonly used as a part of web pages.",
              img: "https://i.postimg.cc/FKGrGDFf/js-Badge-strict-svg.png",
            },
            {
              id: "D",
              brand: "Boostrap",
              price: 1135000,
              model: "Bootstrap is a free and open-source CSS framework directed at responsive, mobile-first front-end web development. It contains HTML, CSS and JS.",
              img: "https://i.postimg.cc/YCPKSZSz/pngaaa-com-5505249.png",
            },
          ],
        };
      },
    };
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
    border: 0px solid black;
    margin-bottom: 2%;
  }
  .card-img-top{
    width: 18rem;
  }

  @media only screen and (max-width: 721px){
    #skills{
      margin-top: 8% !important;
    }
  }

  @media only screen and (max-width: 301px){

    #skills{
      margin-top: 13%;
    }
    .card-holder{
      display: flex;
      flex-wrap: wrap;
      justify-content: space-evenly;
    }
    .card{
      width: 18rem;
      border: 0px solid black;
      margin-bottom: 2%;
    }
    .card-img-top{
      width: 18rem;
    }
  }
</style>