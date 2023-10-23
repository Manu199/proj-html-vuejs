<script>
import Header from './components/Header.vue';
import Partner from './components/Partner.vue';
import Courses from './components/Courses.vue';
import Events from './components/Events.vue';
import Blogs from './components/Blogs.vue';


export default {
  name: 'App',
  components: {
    Header,
    Partner,
    Courses,
    Events,
    Blogs,
  }
}
</script>


<template>
  
  <Header />
  <Partner />
  <Courses />
  <Events />
  <Blogs />
  
</template>


<style>

</style>