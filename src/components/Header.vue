<script setup>
  
</script>

<template>
  <div class="home-container">
    <h1 class="header">Emma Knows Stuff About the Moon</h1>
    <div class="moon-image-container">
      <img class="moon-image" alt="Moon" src="@/assets/moon.png" />
      <div class="moon-facts-container" ng-hide="isMoonFactsHidden">
        <h2 class="facts-header">FACTS</h2>
        <ul class="moon-facts-list">
          <li>The moon controls the tides and human are 70% water so just think about that 🌙😵‍💫</li>
          <li>Also moonlight?? What's up with that??</li>
        </ul>
      </div>
    </div>
    
  </div>
</template>

<style scoped>
.home-container {
  background: black;
  color: #fff;
  font-family: Arial, Helvetica, sans-serif;

  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  height: 100vh;
  width: 100vw;
}

.home-container h1.header {
  margin-top: 2em;
  font-size: 3em;
}

.moon-image-container {
  width: 100%;
  text-align: center;
}
.moon-image-container .moon-image {
  width: 50vw; 
  height: 50vw;
  display: inline-block;
}

.moon-facts-container {
  position: absolute;
}
</style>
