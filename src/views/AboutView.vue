<template>
  <about/>
  <work/>
  <Footer/>
</template>

<script>
import work from '../components/Work.vue'
import about from '../components/About.vue'
import Footer from '../components/Footer.vue';
export default {
  components:{
    about,
    work,
    Footer
}
}
</script>

<style scoped>
  
</style>