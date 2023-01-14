<template>

  <div class="mt-3 mb-5">
    <div data-aos="fade-up" data-aos-duration="700" class="post-heading text-center">
       <h3 class="Test">Bringing Your Vision to Life</h3>
       <hr class="w-75 mx-auto pb-5">
       <p>My mission is to make your website stand out with modern slick design and stylish responsiveness that gives your brand an edge over your competitors</p>
       <p class="mb-5">Here are some Testimonials from Clients who have seen my Work</p>
    </div>
  
    <div data-aos="fade-up" data-aos-duration="700" id="skills" class="container text-center">
        <h3 id="Exp" class="display-4 font-weight-bold mt-5">Testimonials</h3>
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
  </div>
    </template>
    
    <script>
    
    export default {
      data() {
        return {
          products: [
            {
              id: "A",
              brand: "Keren Bruce",
              price: 27900,
              model: "Mishaine has simplistic Web Development style that compliments the color scheme used and gives a professional look and feel to clients.",
              img: "https://i.postimg.cc/HkBsmQrD/IMG-2.jpg",
            },
            {
              id: "B",
              brand: "Luntu Sogeyana",
              price: 140000,
              model: "The Format looks clean and slick with and nice balance of colors and not too much going on at the same time.",
              img: "https://i.postimg.cc/0NKg4mmC/IMG-20221101-WA0026.jpg",
            },
            {
              id: "C",
              brand: "Mkhuseli Mkeyiya",
              price: 1380000,
              model: "Very responsive design with a wide range of devices, this helps with brand awareness and gives clients a comfortable look.",
              img: "https://i.postimg.cc/k4DsJ3qN/IMG-20221101-WA0025-1.jpg",
            },
            {
              id: "D",
              brand: "Timothy Jennike",
              price: 1135000,
              model: "Smart Designs with easy navigation and seamless transition and animation, these makes for happy Clients and satisfied patrons.",
              img: "https://i.postimg.cc/7LR7NCr7/IMG-3573.jpg",
            },
            {
              id: "E",
              brand: "Joel Mukanya",
              price: 1135000,
              model: "Mishaine is a very creative, go-getter, and well-behaved student. He does enjoy working with his classmates and works well on his project.He has gained knowledge of web development, including Bootstrap 5. I will be very delighted to see him get hired as a developer.",
              img: "https://i.postimg.cc/Bb4b0Frd/Joel-Profile2.jpg",
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
    margin: 2%;
    width: 18rem;
    border: 1px solid rgb(212, 175, 55);
  }
  .card-img-top{
    width: 18rem;
  }
  
  @media only screen and (max-width: 721px){
    .Test{
      margin-top: 13% !important;
    }
  }

  @media only screen and (max-width: 301px){

    .Test{
      margin-top: 23% !important;
    }
    .card-holder{
      display: flex;
      flex-wrap: wrap;
      justify-content: space-evenly;
    }
    .card{
      margin: 2%;
      width: 18rem;
      border: 1px solid rgb(212, 175, 55);
    }
    .card-img-top{
      width: 18rem;
    }
  }
</style>