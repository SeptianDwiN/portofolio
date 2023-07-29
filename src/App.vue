<template>
  <div>
    <Navbar></Navbar>
    <HeaderComponent></HeaderComponent>
  <center><Aboutme></Aboutme></center>  
  <Project></Project>
  <Footer></Footer>
  
  </div>
</template>

<script setup>
import Navbar from './components/Navbar.vue';
import HeaderComponent from './components/HeaderComponent.vue'
import Aboutme from './components/Aboutme.vue';
import Project from './components/Project.vue';
import Footer from './components/Footer.vue';

</script>