<template>
  <div class="home">
    <h1>Welcome to the Home Page</h1>
    <!-- You can add more content here as needed -->
  </div>
</template>

<script>
export default {
  name: 'HomeView',
  // Any component-specific logic goes here
}
</script>

<style scoped>
.home {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  width: 100%; /* Take full width */
  height: 100%;
  padding: 1rem; /* Adjust padding as needed */
  box-sizing: border-box;
}

h1 {
  margin: 0;
  /* Add more styling for your h1 element here */
}
</style>



<!-- <template>
  <div class="home">
    <h1>Home</h1>
  </div>
</template>

<style>
  .home {
  width: 100vw; /* Full viewport width */
  min-height: 100vh;
  display: flex;
  align-items: center;
  margin: 0;
  padding: 0;
  background-color: aqua;
}

</style> -->
