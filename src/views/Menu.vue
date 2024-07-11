<template>
  <section class="menu">
    <div class="container">
      <h2 class="menu-title">What's on Offer</h2>
      <div class="menu-container">
        <div class="menu-item">
          <img src="../assets/menu1.jpg" alt="Image 1">
        </div> <!-- First container -->
        <div class="menu-item">
          <img src="../assets/menu2.jpg" alt="Image 2">
        </div> <!-- Second container -->
      </div>
    </div>
  </section>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap');

.menu {
  background-color: #343a40; 
  padding: 50px 0;
  text-align: center;
}

.menu-title {
  font-size: 2.5rem;
  margin-bottom: 30px;
  color: #fff; 
  font-family: 'Roboto', sans-serif;
}

.menu-container {
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap; 
}

.menu-item {
  width: 48%; 
  height: auto; 
  background-color: #fff; 
  border-radius: 10px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  overflow: hidden; 
}

.menu-item img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  border-radius: 10px;
}


@media screen and (max-width: 768px) {
  .menu-item {
    width: 100%; 
    margin-bottom: 20px; 
  }
  body {
  overflow-x: hidden;
}
}
</style>
