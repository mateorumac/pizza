<template>
  <section class="menu">
    <div class="container">
      <h2 class="menu-title">What's on Offer</h2>
      <div class="menu-container">
        <div class="menu-item">
          <img src="../assets/menu1.jpg" alt="Image 1">
        </div>
        <div class="menu-item">
          <img src="../assets/menu2.jpg" alt="Image 2">
        </div>
      </div>
    </div>
  </section>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap');

.menu {
  background-color: #343a40; 
  padding: 50px 20px;
  text-align: center;
}

.menu-title {
  font-size: 2rem;
  margin-bottom: 30px;
  color: #fff; 
  font-family: 'Roboto', sans-serif;
}

.menu-container {
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap; 
  gap: 20px; 
}

.menu-item {
  flex: 1 1 calc(50% - 20px);
  background-color: #fff; 
  border-radius: 10px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  overflow: hidden; 
}

.menu-item img {
  width: 100%;
  height: auto;
  object-fit: cover;
  border-radius: 10px;
}

@media screen and (max-width: 768px) {
  .menu-item {
    flex: 1 1 100%; 
    margin-bottom: 20px; 
  }
  body {
    overflow-x: hidden;
  }
}
</style>
