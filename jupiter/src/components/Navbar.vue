<template>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
      <div class="container-xl"> <!-- Use container-xl for wider container -->
        <!-- Logo and Name -->
        <router-link to="/" class="navbar-brand">
          <img src="../assets/jupiter.png" alt="Logo" class="navbar-logo">
          <span class="navbar-text navbar-title">Pizzeria Jupiter</span>
        </router-link>
  
        <!-- Navbar Toggler for Mobile -->
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
  
        <!-- Navbar Links -->
        <div class="collapse navbar-collapse justify-content-end" id="navbarNav"> <!-- Align links to the right -->
          <ul class="navbar-nav">
            <li class="nav-item">
              <router-link to="/about" class="nav-link">About</router-link>
            </li>
            <li class="nav-item">
              <router-link to="/menu" class="nav-link">Menu</router-link>
            </li>
            <li class="nav-item">
              <router-link to="/news" class="nav-link">News</router-link>
            </li>
            <li class="nav-item">
              <router-link to="/delivery" class="nav-link">Delivery</router-link>
            </li>
            <li class="nav-item">
              <router-link to="/contact" class="nav-link">Contact</router-link>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </template>
  
  <script>
  export default {
    name: 'Navbar'
  }
  </script>
  
  <style scoped>

.navbar {
  padding: 20px 0; 
}
  .navbar-logo {
    height: 55px; 
    width: 55px; 
    border-radius: 50%; 
    margin-right: 10px;
  }
  
  .navbar-title {
    margin-left: 1.5rem;
    font-size: 1.7rem; /* Increase font size for the restaurant name */
  }
  
  .container-xl {
    max-width: 1400px; /* Increase max-width for wider navbar */
  }
  </style>
  