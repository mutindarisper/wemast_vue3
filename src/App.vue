<template>
  <div class="app" >

    <header>
 
    <Navbar />
   
  </header>
  <div class="selections">
    <Selections />

  </div>


  <div class="map_section">
    <Map />

  </div>
   
  </div>
 
   


        <!-- <RouterLink to=""></RouterLink>
        <RouterLink to=""></RouterLink>
  <RouterView /> -->
</template>


<script setup>
import Navbar from './components/Navbar.vue';
import Selections from './components/Selections.vue';
import Map from './components/Map.vue';
</script>


<style scoped>
.nav{
  position: absolute;
      top: -20vh;
      left: 0;
  height: 12vh;
  background-color: rgb(175, 10, 10) !important;
}

</style>
