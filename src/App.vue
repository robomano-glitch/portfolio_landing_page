<template>
  <div class="container overflow-x-hidden">
    <Navbar />
    <Home />
    <TechStack />
    <Projects />
    <WorkExperience />
    <Footer />
  </div>
</template>

<script setup>
  import Navbar from './components/MyNavbar.vue';
  import Home from './components/MyHome.vue';
  import TechStack from './components/TechStack.vue';
  import Projects from './components/MyProjects.vue';
  import WorkExperience from './components/WorkExperience.vue';
  import Footer from './components/MyFooter.vue';
</script>   

<style>
  
</style>
