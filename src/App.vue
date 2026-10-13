<script setup lang="ts">

import AppNavBar from '../component/AppNavBar.vue';
import HomeView from './views/HomeView.vue';


const scrollToSection = (id: string) => {
  document.getElementById(id)?.scrollIntoView({
    behavior: 'smooth'
  });
};

</script>

<template>
  <div>
    <AppNavBar @navigate="scrollToSection"  />
    
    <HomeView/>
  </div>
</template>
