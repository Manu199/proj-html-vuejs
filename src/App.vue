<script>
import Header from './components/Header.vue';
import Partner from './components/Partner.vue';
import Courses from './components/Courses.vue';
import Events from './components/Events.vue';
import Blogs from './components/Blogs.vue';
import Prefooter from './components/Prefooter.vue';
import Footer from './components/Footer.vue';

export default {
  name: 'App',
  components: {
    Header,
    Partner,
    Courses,
    Events,
    Blogs,
    Prefooter,
    Footer
  }
}
</script>


<template>
  
  <Header />
  <Partner />
  <Courses />
  <Events />
  <Blogs />
  <Prefooter />
  <Footer />
  
</template>


<style>

</style>