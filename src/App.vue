<template>
  <div id="app-container">
    <header>
      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </nav>
    </header>

    <RouterView />
  </div>
</template>

<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<style scoped>
#app-container {
  width: 100%;
  height: 100%;
}

header {
  width: 100%;
  height: 50px; /* Fixed height for the header */
  position: fixed;
  top: 0;
  left: 0;
  z-index: 1000;
  background-color: transparent; /* Example background color */
  display: flex;
  justify-content: center;
  align-items: center;
}

nav a {
  margin: 0 10px; /* Spacing between links */
  text-decoration: none;
  color: black; /* Set your desired color */
}

nav a.router-link-exact-active {
  font-weight: bold;
}
</style>


<!-- <script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>
      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </nav>
  </header>

  <RouterView />
</template>

<style scoped>
/* Style for the header (navigation bar) */
header {
  position: fixed; /* Fixed position at the top */
  top: 0; /* Align to the top of the page */
  left: 0; /* Align to the left of the page */
  width: 100%; /* Full width */
  height: 50px; /* 50px height */
  background-color: transparent; /* Background color */
  z-index: 1000; /* Ensure it's above other elements */
}

/* Style for the navigation links */
nav {
  display: flex;
  justify-content: center; /* Center the navigation links */
  align-items: center; /* Vertically align the links */
  height: 100%; /* Full height of the header */
}

/* Style for the main content area */
#app {
  padding-top: 50px; /* Space equal to the height of the header */
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

nav a.router-link-exact-active {
  color: var(--color-text);
}

nav a.router-link-exact-active:hover {
  background-color: transparent;
}

nav a {
  display: inline-block;
  padding: 0 1rem;
  border-left: 1px solid var(--color-border);
}

nav a:first-of-type {
  border: 0;
}


</style> -->
