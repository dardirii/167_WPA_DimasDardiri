<template>
  <Carousel />
  <About />
  <Services />
  <Portofolio />
  <Testimonial />
  <Team />
  <Contact />
</template>

<script>
import Carousel from '../components/Carousel.vue';
import About from '../components/About.vue';
import Services from '../components/Services.vue';
import Portofolio from '../components/Portofolio.vue';
import Testimonial from '../components/Testimonial.vue';
import Team from '../components/Team.vue'
import Contact from '../components/Contact.vue'

export default{
  components: {
    Carousel,
    About,
    Services,
    Portofolio,
    Team,
    Contact,
    Testimonial,
  },
}
</script>
