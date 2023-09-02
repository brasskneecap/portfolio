<script setup lang="ts">
</script>

<template>
  <main class="test">    
    <div class="sounds-container">
      <v-switch></v-switch>
    </div>
    <video autoplay muted loop id="myVideo">
      <source src="@/assets/backgrounds/sky-island-pixel-moewalls-com.mp4" type="video/mp4">
      Any alternate text.
    </video>
  </main>
</template>

<style>

#myVideo {
  position: absolute;
  z-index: 1;
  right: 0;
  bottom: 0;
  min-width: 100%; 
  min-height: 100%;
  
}

.sounds-container {
  z-index: 2;
  height: 500px;
  width: 500px;
  border: 1px solid black;
  background-color: lightblue;
  border-radius: 8px;
  position: absolute;
  top:0;
  bottom: 0;
  left: 0;
  right: 0;  
  margin: auto;
  opacity: .8;
}
</style>