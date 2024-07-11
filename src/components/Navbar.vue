<template>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container-xl d-flex justify-content-between align-items-center">
      <router-link to="/" class="navbar-brand">
        <img src="../assets/jupiter.png" alt="Logo" class="navbar-logo">
        <span class="navbar-text navbar-title">Pizzeria Jupiter</span>
      </router-link>
     
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item">
            <router-link to="/about" class="nav-link">About</router-link>
          </li>
          <li class="nav-item">
            <router-link to="/menu" class="nav-link">Menu</router-link>
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
@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');

.navbar {
  padding: 5px 0; 
}

.navbar-logo {
  height: 70px; 
  width: auto; 
  border-radius: 50%; 
  margin-right: 10px;
  transition: transform 0.5s ease-in-out; 
}

.navbar-logo:hover {
  transform: rotate(360deg); 
}

.navbar-title {
  margin-left: 1.5rem;
  font-size: 2rem; 
  font-family: "Poppins", sans-serif;
  font-weight: 500;
  color: yellow; 
}

.navbar-nav .nav-item .nav-link {
  font-family: "Poppins", sans-serif; 
  color: white; 
  font-size: 1.4rem;
  position: relative;
}

.navbar-nav .nav-item .nav-link::after {
  content: '';
  position: absolute;
  left: 50%;
  transform: translateX(-50%);
  bottom: -2px; 
  width: 70%; 
  height: 2px;
  background-color: yellow; 
  opacity: 0; 
  transition: opacity 0.3s ease-in-out; 
}

.navbar-nav .nav-item .nav-link:hover::after {
  opacity: 1; 
}

.navbar-nav {
  margin-left: auto;
}
</style>
