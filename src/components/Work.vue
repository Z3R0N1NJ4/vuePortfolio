<template>
    <div data-aos="fade-up" data-aos-duration="700" id="skills" class="container text-center">
        <h3 id="Exp" class="display-4 font-weight-bold mt-5">Resume</h3>
        <hr class="w-50 mx-auto pb-5">
      </div>
      <div data-aos="fade-up" data-aos-duration="950" class="card-holder">
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
              brand: "Life Choices Academy-Started 26 Sep 2022",
              price: 27900,
              model: "Life Choices is a small yet powerful NPO based in Cape Town, since 2005 and have impacted over 200 000 people with choices, not charity working with youth from the Cape Flats communities to make choices that can change the world.",
              img: "https://i.postimg.cc/ZRv56LSt/download-LCA.png",
            },
            {
              id: "B",
              brand: "AWS Certified Cloud Practitioner-Issued 08 Apr 2022",
              price: 140000,
              model: "Earners of this certification have a fundamental understanding of IT services and their uses in the AWS Cloud. They demonstrated cloud fluency and foundational AWS knowledge. We are able to identify essential AWS services necessary to set up AWS-focused projects.",
              img: "https://i.postimg.cc/GhP3d2KR/imageAWS.png",
            },
            {
              id: "C",
              brand: "IBM:Cloud Intro-Issued March 30 2021",
              price: 1380000,
              model: "Through self-paced learning, this badge was earned through the understanding of topics such as cloud computing, cloud, IaaS, PaaS, SaaS, Hybrid Cloud, Private Cloud, data storage, and flexible infrastructure.",
              img: "https://i.postimg.cc/yxMM2wWn/IDN-Emerging-Tech-Cloud.png",
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
  }
  .card-img-top{
    width: 18rem;
  }
</style>