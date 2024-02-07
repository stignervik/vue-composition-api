<template>
  <div class="about">
    <h1>Welcome to the About Page</h1>
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
.about {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  width: 100%; /* Take full width */
  height: 100%; /* Adjust height considering the header */
  padding: 1rem; /* Adjust padding as needed */
  box-sizing: border-box;
}

h1 {
  margin: 0;
  /* Add more styling for your h1 element here */
}
</style>


<!-- <template>
  <div class="about">
    <h1>This is an about page</h1>
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    width: 100%; /* Full width */
    min-height: 100vh;
    display: flex;
    align-items: center;
    margin: 0; /* Reset margin */
    padding: 0; /* Reset padding */
    
  }
}
</style> -->
